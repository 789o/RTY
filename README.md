body {
  font-family: 'Cairo', Tahoma, Arial, sans-serif;
  background: #f7f8fa;
  margin: 0;
  direction: rtl;
  transition: background 0.4s,color 0.4s;
}
body.dark-mode {
  background: #171a22;
  color: #e3e3e3;
}
.header {
  background: #003366;
  color: #fff;
  padding: 10px 0 10px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: relative;
}
.header .logo {
  height: 55px;
  margin-right: 25px;
}
.header h1 {
  flex: 1;
  text-align: center;
  font-size: 2rem;
  letter-spacing: 1px;
}
.logout-btn, .lang-btn, .mode-btn {
  margin-left: 10px;
  padding: 7px 16px;
  background: #0071c5;
  color: #fff;
  border: none;
  border-radius: 18px;
  cursor: pointer;
  font-size: 1rem;
  transition: background 0.2s;
}
.logout-btn { background: #c00; }
.lang-btn { background: #009688; }
.mode-btn { background: #2c2c2c; font-size: 1.2rem;}
body.dark-mode .header, body.dark-mode .footer {
  background: #181e29;
  color: #e3e3e3;
}
.notifications {
  background: #ffe9b3;
  color: #7a4600;
  padding: 12px 18px;
  font-weight: bold;
  border-bottom: 2px solid #ffd44f;
  display: none;
  text-align: center;
  font-size: 1.08rem;
}
body.dark-mode .notifications {
  background: #2a2323;
  color: #ffb74d;
  border-bottom: 2px solid #ff9800;
}
.container {
  display: flex;
  min-height: 80vh;
}
.sidebar {
  background: #ececec;
  width: 220px;
  min-height: 100%;
  padding: 0;
  border-left: 2px solid #d8d8d8;
}
body.dark-mode .sidebar {
  background: #22242a;
  border-left: 2px solid #252b39;
}
.sidebar ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
.sidebar li {
  border-bottom: 1px solid #ddd;
}
body.dark-mode .sidebar li {
  border-bottom: 1px solid #252b39;
}
.sidebar a {
  display: block;
  padding: 13px 22px;
  text-decoration: none;
  color: #003366;
  font-weight: bold;
  transition: background 0.2s;
}
.sidebar a.active, .sidebar a:hover {
  background: #d3e7fa;
  color: #0071c5;
}
body.dark-mode .sidebar a {
  color: #b8e0ff;
}
body.dark-mode .sidebar a.active, body.dark-mode .sidebar a:hover {
  background: #004f7c;
  color: #fff;
}
.main-content {
  flex: 1;
  padding: 35px 28px;
  background: #fff;
  min-height: 80vh;
  transition: background 0.4s,color 0.4s;
}
body.dark-mode .main-content {
  background: #1c2029;
  color: #e3e3e3;
}
.hidden {
  display: none !important;
}
.login-form {
  max-width: 330px;
  margin: 80px auto 0 auto;
  background: #f4f7fb;
  padding: 30px 25px;
  border-radius: 12px;
  box-shadow: 0 2px 8px #0001;
  display: flex;
  flex-direction: column;
  gap: 13px;
}
body.dark-mode .login-form { background: #22242a; color: #eee; }
.login-form label {
  font-weight: bold;
}
.login-form input {
  padding: 8px;
  border-radius: 6px;
  border: 1px solid #ccc;
  font-size: 1rem;
  background: #fff;
}
body.dark-mode .login-form input {
  background: #323844;
  color: #fff;
  border: 1px solid #444;
}
.login-form button {
  background: #003366;
  color: #fff;
  padding: 10px;
  border: none;
  border-radius: 7px;
  font-size: 1.1rem;
  cursor: pointer;
}
.profile-box {
  display: flex;
  align-items: flex-start;
  background: #f4f7fb;
  border-radius: 10px;
  box-shadow: 0 2px 8px #0001;
  padding: 28px 28px;
  max-width: 580px;
  gap: 18px;
}
body.dark-mode .profile-box {
  background: #232733;
  color: #eee;
}
.profile-box img {
  width: 110px;
  height: 110px;
  border-radius: 60px;
  object-fit: cover;
  border: 2px solid #0071c5;
}
.profile-box table th {
  text-align: right;
  font-weight: bold;
  color: #003366;
  padding-left: 12px;
}
body.dark-mode .profile-box table th {
  color: #aad;
}
.profile-box table td {
  color: #222;
}
body.dark-mode .profile-box table td {
  color: #e3e3e3;
}
.data-table {
  width: 100%;
  border-collapse: collapse;
  background: #fafbfe;
  margin-top: 25px;
  font-size: 1.08rem;
}
body.dark-mode .data-table {
  background: #242832;
  color: #e1e1e1;
}
.data-table th, .data-table td {
  padding: 8px 8px;
  border: 1px solid #d9e3ef;
  text-align: center;
}
body.dark-mode .data-table th, body.dark-mode .data-table td {
  border: 1px solid #384160;
}
.data-table th {
  background: #e3eefc;
  color: #003366;
}
body.dark-mode .data-table th {
  background: #004f7c;
  color: #fff;
}
.quick-links {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}
.quick-links li a {
  background: #e3eefc;
  color: #003366;
  padding: 14px 28px;
  text-decoration: none;
  border-radius: 7px;
  font-weight: bold;
  border: 1px solid #b5c9ea;
  transition: background 0.2s, color 0.2s;
}
.quick-links li a:hover {
  background: #003366;
  color: #fff;
}
body.dark-mode .quick-links li a {
  background: #004f7c;
  color: #fff;
  border: 1px solid #448cc7;
}
.file-list {
  list-style: none;
  padding: 0;
  margin-top: 20px;
}
.file-list li {
  margin-bottom: 13px;
}
.file-list a {
  background: #f1f5fa;
  color: #003366;
  padding: 10px 17px;
  border-radius: 6px;
  font-weight: bold;
  text-decoration: none;
  border: 1px solid #c3d3ea;
  transition: all 0.2s;
}
.file-list a:hover {
  background: #0071c5;
  color: #fff;
}
body.dark-mode .file-list a {
  background: #23344a;
  color: #e3e3e3;
  border: 1px solid #448cc7;
}
.support-form, .complaint-form, .advisor-form, .settings-form, .update-profile-form, .messages-form {
  max-width: 430px;
  background: #f4f7fb;
  padding: 22px 18px;
  border-radius: 10px;
  box-shadow: 0 2px 8px #0001;
  display: flex;
  flex-direction: column;
  gap: 12px;
}
body.dark-mode .support-form, body.dark-mode .complaint-form, body.dark-mode .advisor-form,
body.dark-mode .settings-form, body.dark-mode .update-profile-form, body.dark-mode .messages-form {
  background: #232733;
  color: #eee;
}
.support-form textarea, .complaint-form textarea, .advisor-form select, .messages-form input {
  resize: vertical;
  border-radius: 7px;
  border: 1px solid #bbb;
  font-size: 1.1rem;
  padding: 8px;
}
body.dark-mode .support-form textarea, body.dark-mode .complaint-form textarea, 
body.dark-mode .advisor-form select, body.dark-mode .messages-form input {
  background: #323844;
  color: #fff;
  border: 1px solid #444;
}
.support-form button, .complaint-form button, .advisor-form button, .settings-form button, .update-profile-form button, .messages-form button {
  background: #0071c5;
  color: #fff;
  border: none;
  padding: 10px;
  border-radius: 6px;
  font-size: 1.1rem;
  cursor: pointer;
}
.messages-form {
  flex-direction: row;
  gap: 5px;
  margin-top: 15px;
  background: none;
  box-shadow: none;
  padding: 0;
}
#messages-box {
  max-height: 200px;
  overflow-y: auto;
  background: #f4f7fb;
  border-radius: 7px;
  padding: 10px;
  margin-bottom: 8px;
}
body.dark-mode #messages-box {
  background: #232733;
  color: #fff;
}
#messages-box .msg-out {
  text-align: right;
  color: #0071c5;
  margin-bottom: 7px;
}
#messages-box .msg-in {
  text-align: left;
  color: #c00;
  margin-bottom: 7px;
}
.footer {
  background: #003366;
  color: #fff;
  text-align: center;
  padding: 17px 0 10px 0;
  font-size: 1rem;
  letter-spacing: 1px;
  margin-top: 40px;
}
body.dark-mode .footer {
  background: #181e29;
  color: #e3e3e3;
}
#calendar-box {
  background: #f7f8fa;
  border-radius: 12px;
  padding: 15px 12px;
  margin-top: 10px;
  max-width: 450px;
  border: 1px solid #e3eefc;
}
body.dark-mode #calendar-box {
  background: #232733;
  border: 1px solid #448cc7;
}
#advisor-confirm, #complaint-status {
  margin-top: 12px;
  font-weight: bold;
  color: #0071c5;
}
@media (max-width: 900px) {
  .container {
    flex-direction: column;
  }
  .sidebar {
    width: 100%;
    border-left: none;
    border-bottom: 2px solid #d8d8d8;
    display: flex;
    flex-direction: row;
    overflow-x: auto;
  }
  .sidebar ul {
    display: flex;
    flex-direction: row;
    width: 100%;
    gap: 0;
  }
  .sidebar li {
    flex: 1;
    border-bottom: none;
    border-left: 1px solid #ddd;
  }
  .sidebar li:first-child {
    border-left: none;
  }
  .sidebar a {
    padding: 15px 9px;
    text-align: center;
  }
  .main-content {
    padding: 17px 7px;
  }
  .profile-box {
    flex-direction: column;
    align-items: center;
    padding: 18px 7px;
  }
}
@media (max-width: 600px) {
  .header h1 {
    font-size: 1.2rem;
  }
  .profile-box table {
    font-size: 0.95rem;
  }
  .data-table {
    font-size: 0.94rem;
  }
let studentData = {
  id: '20231234',
  name: 'علي صابر محمد',
  dept: 'علوم الحاسب',
  year: 'الفرقة الثالثة', // تم التعديل هنا
  code: '20231234',
  email: '20231234@mans.edu.eg',
  password: '1234',
  photo: 'student.png',
  phone: '01123456789',