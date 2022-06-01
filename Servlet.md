# SERVLET

## MVC With Servlet and JSP
1. Idea : Sử dụng Servlet làm controller, jsp làm view
2. Servlet can call JSP using a request dispatcher object: `RequestDispatcher dispatcher = request.getRequestDispatcher("/tenView");`
3. `dispatcher.forward(request, response);` : Gửi thông tin request và response đến file JSP
4. Sending data to JSP:
 - `request.setAttribute("tenMuonDat", dataCanGui);`
5. JSP use JSTL to access data from request
