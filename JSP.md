
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


## JSP Standard Tag Library & Custom Tag
### JSP Standard Tag Library (JSTL)
#### JSTL Core tags https://www.javatpoint.com/jstl-core-tags
22. `<c:catch />` : 
23. `<c:when >` :
24. `<c:choose > <c:when > write your code </c:when > <c:otherwise> write your code </c:otherwise> </c:choose >` :
25. `<c:otherwise>` :
26. `<c:if test="${tempStudent.goldCustomer }">Data can thien thi </c:if>` : core if tag hien thi theo dieu kien
27. `<c:import />` :
28. `<c:forEach> write your code here </c:forEach>` :
29. `<c:forTokens />` :
30. `<c:out />` :
31. `<c:param />` :
32. `<c:redirect />` :
33. `<c:remove />` :
34. `<c:set />` :
35. `<c:url />` :

#### JSTL function tags https://www.javatpoint.com/jstl-function-tags
36. `<%@ taglib uri="http://java.sun.com/jsp/jstl/functions" prefix="fn" %>` : insert this code to use function tags
37. ${fn:length("text or variable")}
38. ${fn:toUpperCase(String)}
39. fn:contains()
40. fn:containsIgnoreCase()
41. fn:endsWith()
42. fn:escapeXml()
43. fn:indexOf()
44. fn:trim()
45. fn:startsWith()
46. fn:split()
47. fn:substring()
48. fn:substringAfter()
49. fn:replace()

#### JSTL Formatting tags https://www.javatpoint.com/jstl-formatting-tags
50. <%@ taglib uri="http://java.sun.com/jsp/jstl/fmt" prefix="fmt"  %>  
51. <fmt:parseNumber var="j" integerOnly="true" type="number" value="${Amount}" /> 
52. fmt:timeZone
53. fmt:formatNumber
54. fmt:parseDate
55. fmt:bundle
56. fmt:setTimeZone
57. fmt:setBundle
58. fmt:message
59. fmt:formatDate

 
