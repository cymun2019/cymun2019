---
layout: default
title: Staff Registration
permalink: /staff-registration/
robots: noindex
---
<h2>Đơn đăng ký làm ban tổ chức CYMUN 2019</h2>
Thông tin cá nhân
<form method="POST" action="https://formspree.io/cymun2019.official@gmail.com">
  <textarea name="Loại đơn" style="visibility: hidden;">BAN TỔ CHỨC</textarea>
	   <div class="group">      
    <input type="text" required name="Họ và tên">
      <span class="highlight"></span>
      <span class="bar"></span>
     <label>Họ và tên</label>
   </div>

   <div class="group">      
<input type="date" class="form-control" id="Date of birth" name="Ngày tháng năm sinh" placeholder="Date of Birth">
      <span class="highlight"></span>
      <span class="bar"></span>
     <label>Ngày tháng năm sinh</label>
   </div>


  <div class="group" style="margin-top: 50">      
    <input type="text" required name="Email">
      <span class="highlight"></span>
      <span class="bar"></span>
     <label>Địa chỉ email</label>
   </div>
     <div class="group">      
    <input type="text" required name="Facebook link">
      <span class="highlight"></span>
      <span class="bar"></span>
     <label>Link Facebook cá nhân</label>
   </div>
     <div class="group">      
    <input type="number" required name="SĐT">
      <span class="highlight"></span>
      <span class="bar"></span>
     <label>Số điện thoại</label>
   </div>   
        <div class="group">      
    <input type="text" required name="Lớp">
      <span class="highlight"></span>
      <span class="bar"></span>
     <label>Lớp</label>
   </div>   
     <p>Bạn dự định vào ban nào ?</p>
<div class="custom-select" style="width:340px; margin-bottom:22px;" >
  <select name="Ban" id="select1">
    <option value="none">Chọn ban:</option>
    <option value="Media">Ban media</option>
    <option value="Design">Ban design</option>
    <option value="4">Ban nội dung</option>
    <option value="Tài chính">Ban tài chính</option>
    <option value="Đối ngoại">Ban đối ngoại</option>
    <option value="Truyền thông">Ban truyền thông</option>
  </select>
</div>
<div id="bannoidung" style="visibility: hidden;">
<p>Câu hỏi ban nội dung: Express your opinions on a global issue and suggest some solutions to it?</p>
  <textarea name="Câu hỏi ban nội dung"></textarea>
</div>
<br>

<SCRIPT>

function message() {

var s = document.getElementById('select1');
var item1 = s.options[s.selectedIndex].value;
var item2 = document.getElementById('bannoidung').style.visibility;

if (item1 == 4) {
document.getElementById("check_fail").style.visibility = "visible"; 
  document.getElementById("bannoidung").style.visibility = "visible";
if (item2 == "visible") {
document.getElementById("check_fail").style.visibility = "hidden"; 
document.getElementById("check_done").style.visibility = "visible"; 
document.getElementById("button2").style.visibility = "visible"; 
document.getElementById("button").style.visibility = "hidden";
}
}
else {
document.getElementById("check_done").style.visibility = "visible"; 
document.getElementById("button2").style.visibility = "visible"; 
document.getElementById("button").style.visibility = "hidden"; 
}
}

</SCRIPT>
<p style="visibility: hidden; color: green;" id="check_done">Đơn của bạn hợp lệ và sẵn sàng để gửi!</p>
<p style="visibility: hidden; color: red;" id="check_fail">Đơn của bạn chưa sẵn sàng để gửi! Vui lòng trả lời câu hỏi dành cho phần ban nội dung.</p>
<button style="visibility: hidden;" class="btn btn-white btn-animation-1 trigger" type="submit" id="button2">GỬI ĐƠN!</button>
</form>
<button style="display: block;" class="btn btn-white btn-animation-1" id="button" onclick="message()">CHECK LẠI ĐƠN</button>
