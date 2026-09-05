1. Luôn trả lời bằng tiếng Việt.
2. Không tạo hàm `static`.
3. Không dùng `try`/`catch`.
4. Trước khi triển khai thay đổi, phải xác nhận đã hiểu yêu cầu, giải thích lại hướng làm, rồi chờ bạn cho phép.
5. Trước mỗi commit phải kiểm tra:
   - `git status --short`
   - `git diff --cached --name-only`
   - staged diff
6. Commit phải chia nhỏ theo từng hạng mục rõ ràng, dễ cherry-pick/revert.
7. Không tạo commit gộp nếu staged index có nhiều hạng mục không liên quan.
8. Chỉ commit staged changes, không tự stage file unstaged để commit.
9. Nếu staged index có nhiều hạng mục, phải hỏi trước khi sắp xếp lại index.
10. Nếu được phép sắp xếp lại index, chỉ unstage/restage file đã staged sẵn, không kéo thêm unstaged changes.
11. Commit message phải mô tả đúng một hạng mục.
12. Trước khi `reset`, `amend`, hoặc `rebase`, phải xác minh commit chưa push và xin phép rõ.
13. Không push nếu bạn chưa yêu cầu rõ.

Lưu ý: file `/Users/phutranquang/Downloads/SKILL.md` hiện **không tồn tại** trong môi trường này, nên skill Big Two ở path đó không còn thấy được.
