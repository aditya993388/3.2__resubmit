<template>
    <footer class="footer">
      <div class="footer-content">
        <div class="footer-item">
          <h4>Contact</h4>
          <p>Email: aditya@gmail.com</p>
          <p>Phone: +1234567890</p>
        </div>
        <div class="footer-item">
          <h4>Follow Me</h4>
          <ul class="social-icons">
            <li><a href="https://www.linkedin.com/your-profile" target="_blank"><i class="fab fa-linkedin"></i></a></li>
            <li><a href="https://www.instagram.com/your-profile" target="_blank"><i class="fab fa-instagram"></i></a></li>
            <li><a href="https://www.facebook.com/your-profile" target="_blank"><i class="fab fa-facebook"></i></a></li>
          </ul>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer',
  };
  </script>
  
  <style scoped>
  .footer {
    background-color: #75a7dd;
    color: #ffffff;
    padding: 20px 0;
    text-align: center;
  }
  
  .footer-content {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
  }
  
  .footer-item {
    flex: 1;
    margin: 10px;
    text-align: center;
  }
  
  .footer h4 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .footer p {
    margin: 0;
  }
  
  .social-icons {
    list-style: none;
    padding: 0;
  }
  
  .social-icons li {
    display: inline;
    margin-right: 10px;
  }
  
  .social-icons a {
    color: #fff;
    text-decoration: none;
    font-size: 24px;
  }
  </style>
  