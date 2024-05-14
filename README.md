# Test Plan ISTQB

1.  **Introduction (Giới thiệu)**
    
    *   Mô tả về mục đích và phạm vi của kế hoạch kiểm thử.
        
    *   Các bên liên quan và người chịu trách nhiệm.
        
2.  **Test Items (Các mục kiểm thử)**
    
    *   Danh sách các mục phần mềm sẽ được kiểm thử (các module, chức năng).
        
3.  **Features to be Tested (Các tính năng sẽ được kiểm thử)**
    
    *   Liệt kê các tính năng và chức năng cụ thể của hệ thống cần kiểm thử.
        
4.  **Features Not to be Tested (Các tính năng không được kiểm thử)**
    
    *   Các tính năng và chức năng sẽ không được kiểm thử cùng với lý do.
        
5.  **Approach (Phương pháp)**
    
    *   Chiến lược và phương pháp kiểm thử tổng thể.
        
    *   Các loại kiểm thử sẽ được thực hiện (kiểm thử chức năng, kiểm thử phi chức năng, kiểm thử hồi quy, v.v.).
        
6.  **Item Pass/Fail Criteria (Tiêu chí đánh giá đạt/không đạt)**
    
    *   Xác định tiêu chí cụ thể để quyết định xem mục kiểm thử có đạt yêu cầu hay không.
        
7.  **Test Deliverables (Các sản phẩm kiểm thử)**
    
    *   Liệt kê tất cả các tài liệu và sản phẩm sẽ được giao nộp trong quá trình kiểm thử (test cases, test scripts, test data, báo cáo kiểm thử, v.v.).
        
8.  **Testing Tasks (Các nhiệm vụ kiểm thử)**
    
    *   Mô tả các nhiệm vụ cụ thể cần thực hiện trong quá trình kiểm thử.
        
9.  **Environmental Needs (Yêu cầu môi trường)**
    
    *   Các yêu cầu về môi trường kiểm thử (phần cứng, phần mềm, công cụ, thiết lập mạng, cấu hình hệ thống).
        
10.  **Responsibilities (Trách nhiệm)**
    
    *   Xác định rõ trách nhiệm của từng thành viên trong nhóm kiểm thử và các bên liên quan.
        
11.  **Staffing and Training Needs (Nhu cầu nhân lực và đào tạo)**
    
    *   Yêu cầu về nhân lực và bất kỳ chương trình đào tạo nào cần thiết cho đội ngũ kiểm thử.
        
12.  **Schedule (Lịch trình)**
    
    *   Lịch trình kiểm thử chi tiết, bao gồm thời gian bắt đầu và kết thúc cho từng giai đoạn kiểm thử.
        
13.  **Risks and Contingencies (Rủi ro và phương án dự phòng)**
    
    *   Xác định các rủi ro có thể xảy ra và kế hoạch đối phó với chúng.
        
14.  **Approvals (Phê duyệt)**
    
    *   Danh sách các bên liên quan cần phê duyệt kế hoạch kiểm thử và các thay đổi liên quan.
        

Dưới đây là một ví dụ về kế hoạch kiểm thử đơn giản theo chuẩn ISTQB:

### Test Plan Example

#### 1\. Introduction

*   **Purpose:** Kiểm thử hệ thống quản lý bán hàng.
    
*   **Scope:** Kiểm thử các chức năng chính như quản lý sản phẩm, quản lý khách hàng, xử lý đơn hàng.
    
*   **Stakeholders:** Đội phát triển, đội kiểm thử, quản lý dự án.
    

#### 2\. Test Items

*   **Modules:** Quản lý sản phẩm, Quản lý khách hàng, Xử lý đơn hàng.
    

#### 3\. Features to be Tested

*   **Product Management:** Thêm, sửa, xóa sản phẩm.
    
*   **Customer Management:** Thêm, sửa, xóa khách hàng.
    
*   **Order Processing:** Tạo, cập nhật, hủy đơn hàng.
    

#### 4\. Features Not to be Tested

*   **Advanced Analytics:** Sẽ không kiểm thử các tính năng phân tích nâng cao.
    

#### 5\. Approach

*   **Functional Testing:** Kiểm thử các chức năng theo yêu cầu.
    
*   **Regression Testing:** Kiểm thử hồi quy để đảm bảo không có lỗi mới khi có thay đổi.
    

#### 6\. Item Pass/Fail Criteria

*   **Pass:** Tất cả các test case phải đạt 100% yêu cầu.
    
*   **Fail:** Bất kỳ test case nào không đạt yêu cầu sẽ được coi là thất bại.
    

#### 7\. Test Deliverables

*   **Test Cases**
    
*   **Test Scripts**
    
*   **Test Data**
    
*   **Test Reports**
    

#### 8\. Testing Tasks

*   **Task 1:** Tạo test cases và test scripts.
    
*   **Task 2:** Chuẩn bị dữ liệu kiểm thử.
    
*   **Task 3:** Thực hiện kiểm thử và ghi nhận kết quả.
    

#### 9\. Environmental Needs

*   **Hardware:** Máy chủ kiểm thử với cấu hình tối thiểu.
    
*   **Software:** Hệ điều hành, trình duyệt web, công cụ kiểm thử tự động.
    

#### 10\. Responsibilities

*   **Test Lead:** Quản lý toàn bộ quá trình kiểm thử.
    
*   **Testers:** Thực hiện các test cases và báo cáo lỗi.
    

#### 11\. Staffing and Training Needs

*   **Staffing:** 2 testers, 1 test lead.
    
*   **Training:** Đào tạo về công cụ kiểm thử mới.
    

#### 12\. Schedule

*   **Test Planning:** 1 tuần.
    
*   **Test Execution:** 2 tuần.
    
*   **Reporting:** 1 tuần.
    

#### 13\. Risks and Contingencies

*   **Risk:** Thiếu dữ liệu kiểm thử.
    
*   **Contingency Plan:** Sử dụng dữ liệu mô phỏng nếu cần.
    

#### 14\. Approvals

*   **Project Manager:** Phê duyệt kế hoạch kiểm thử.
    
*   **Development Lead:** Phê duyệt các thay đổi liên quan đến kiểm thử.
