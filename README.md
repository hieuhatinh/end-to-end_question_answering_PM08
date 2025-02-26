# End-to-End Question Answering Project - PM08 - AIO2024

## Giới thiệu
**End-to-end Question Answering** là một bài toán thuộc lĩnh vực Xử lý ngôn ngữ tự nhiên liên quan đến việc xây dựng một hệ thống hỏi đáp sử dụng công cụ truy vấn để tìm kiếm các tài liệu có liên quan đến câu hỏi, từ đó lựa chọn câu trả lời phù hợp nhất đến người dùng

Ngoài ra, **End-to-end Question Answering** cũng là một ý tưởng tiền đề cho **Retrieval Augmented Generation (RAG)**

Project này xây dựng dựa trên bộ dataset SQuAD2.0, vector database là FAISS và mô hình BERT để thực hiện các nhiệm vụ

Hai module chính trong project bao gồm: 
- **Retriever:** Thành phần truy vấn tài liệu có liên quan đến câu hỏi có trong cơ sở dữ liệu

- **Reader:** Dựa trên các tài liệu truy vấn được và câu hỏi đầu vào, trích xuất vùng văn bản chứa câu trả lời chính xác nhất và gửi tới người dùng
![Pipeline End-to-End Question Answering Project](/image_readme/pipeline.png "Tài liệu AIO2024 - PM08W02")