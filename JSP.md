
### JSP Elements
1. `<%= %>` : JSP Expression, in ra 1 chuoi ky tu, gia tri tinh toan, phep so sanh true false
2. `<% java code %>` : JSP Scriptlets,  viet java code như khai báo biến, in biểu thức, khởi tạo object
3. `<%! %>` : JSP Declaration, Khai báo biến, method, goi method trong cung 1 trang jsp
4. `<%@page import="phuoc.learnjsp.FunUtils"%>` : import Class vao trong file jsp, có thể import nhiều package từ đây

### JSP Buit-in Server Object
5. request : Contains HTTP request headers and form data
6. respone : provive HTTP support for sendding respone
7. out : jspWritter for including content in HTML page
8. session : unique session for each user in web application
9. application : 

### Including Files with JSP
10: `<jsp:include page = "ten file"/>` : include 1 file nào đó vào file jsp hiện tại 

### Get Form data
11. `<%= request.getParameter("tenCuaThe")%>` : Lấy thông tin input của thẻ trong form
12. ${param.tenCuaThe} : Lấy thông tin input của thẻ trong form

### Directive tag (The chi thi)
13. `<%@page import="ten packge java"%>` : chỉ thị cần import cái gì đó
14. `<%@include file="ten file"%>` : chỉ thị cần include file nào đó
15. `<%@ taglib prefix = "c" uri = "http://abc.dcss/ahad"%>` : khai báo sử dụng thẻ lib

### Action tag (Thẻ hành động)
16. `<jsp:include page=" abc">` : include file đó vào
17. `<jsp:forward page="abc">` : chuyển request đến trang jsp hoặc servlet hoặc html khác
18. `<jsp:param name="ten" vaule="gia tri">` : thường đi với <jsp:forward> để gửi thêm dữ liệu đi đến nơi khác, cũng có thể kết hợp với các thẻ khác
19. `<jsp:useBean id="abc" class="ClassName">` : chỉ định JSP sử dụng một JavaBean Instance nào
20. `<jsp:setProperty name="id cua bean o tren" property="">` : set a property cho 1 javaBean Instance
21. `<jsp:getProperty>` : lấy 1 thuộc tính của 1 JavaBean Instance được chỉ định

### JSP Standard Tag Library (JSTL)
#### JSTL Core tags
22. `<c:catch />` : 
23. `<c:choose />` :
24. `<c:if />` :
25. `<c:import />` :
26. `<c:forEach />` :
27. `<c:forTokens />` :
28. `<c:out />` :
29. `<c:otherwise />` :
30. `<c:param />` :
31. `<c:redirect />` :
32. `<c:remove />` :
33. `<c:set />` :
34. `<c:url />` :
35. `<c:when />` :
36. 

 
