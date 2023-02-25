# <h1 align="center">Framework_IS220.N11<h1>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="">
  </a>

  <h3 align="center">NFT Charity</h3>

  <p align="center">
    <br />
    <a href="https://github.com/hadanhtuan/NFT_Charity"><strong>Khám phá »</strong></a>
    <br />
    <br />
    <a href="#giaodien">Xem Demo</a>
    ·
    <a href="https://github.com/hadanhtuan/NFT_Charity/issues">Báo lỗi</a>
    ·
    <a href="https://github.com/hadanhtuan/NFT_Charity/issues">Các yêu cầu</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Mục lục</summary>
  <ol>
    <li>
      <a href="#noidung">Nội dung đề tài</a>
    </li>
    <li>
      <a href="#dsthanhvien">Danh sách thành viên</a>
    </li>
    <li><a href="#framework">Công nghệ sử dụng</a></li>
    <li>
      <a href="#chucnang">Các chức năng</a>
    </li>
    <li>
      <a href="#giaodien">Giao diện</a>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## <h2 id="noidung">1. Nội dung đề tài</h2>
<h4>Nội dung</h3> 
Đây là project của môn học Xây dựng hệ thống thông tin trên các Framework. NFT Charity Là một nền tảng giúp cho các doanh nghiệp, tổ chức từ thiện có nhu cầu khởi động chiến dịch từ thiện và kêu gọi đóng góp đến mọi người trên toàn thế giới bằng hình thức đấu giá NFT. Người dùng có thể tạo và quản lý NFT, tham gia đấu giá đồng thời quản lý các giao dịch trên nền tảng này.

<h4>Phạm vi</h4>
-	Hiểu biết tổng quát về quy trình phát triển ứng dụng web.<br>
-	Phạm vi nghiên cứu giới hạn ở việc chỉ có thể tạo NFT, giao dịch coin ETH và mua bán NFT bằng ETH ở mạng Ethereum.

<h4>Đối tượng sử dụng</h4>
-	Hệ thống nhắm đến đối tượng sử dụng là những người hiểu biết kiến thức cơ bản về blockchain và tiền điện tử.

## <h2 id="dsthanhvien">2. Các thành viên tham gia project</h2>
 
| STT| Họ tên         | MSSV                 | FB                                                   |   SĐT     |     Nhiệm vụ    |
|:--:|----------------|------------------------|----------------------------------------------------|-----------|-----------------|
| 1  | Hà Danh Tuấn       | 20522109 |[Hà Tuấn](https://www.facebook.com/danhtu.ha.5)         |0936225132 |Trưởng nhóm      |
| 2  | Phạm Quang Hòa        | 20520995 |[Quang Hòa](https://www.facebook.com/hoapham.Z)           | |Code frontend    |
| 3  | Trần Quốc Bảo     | 20521110 |[Quốc Bảo](https://www.facebook.com/TheBlueStarZ) | |Code backend   |    


## <h2 id="framework">3. Các công nghệ sử dụng</h2>

Trang web được xây dựng bởi các thư viện, framework hiện đại:
* Frontend: [React.js](https://reactjs.org/) + [MaterialUI](https://mui.com/) + [EthersJS](https://docs.ethers.org/v5/)
* Backend: [PHP Laravel](https://laravel.com/) + [MySQL](https://www.mysql.com/)
* Smart-contract: [Solidity](https://docs.soliditylang.org/en/v0.8.19/)
* Others: [XAMPP](https://www.apachefriends.org/download.html) + [Cloudinary](https://cloudinary.com/) + [HardHat](https://hardhat.org/) + [MetaMask](https://metamask.io/)

## <h2 id="chucnang">4. Tóm tắt chức năng</h2>
- Khách hàng:<br/>
  + Đăng nhập bằng MetaMask
  + Tạo NFT
  + Tham gia đấu giá
  + Từ thiện ETH trực tiếp
  + Xem thông tin lịch sử giao dịch
  + Tra cứu NFT, lịch sử giao dịch
  + Quản lý tài khoản, xem thông tin NFT đang sở hữu <br/>
- Admin:<br/>
  + Quản lý các NFT đang sở hữu
  + Tạo và quản lý chiến dịch từ thiện
  + Tạo đấu giá(gắn 1 NFT với 1 chiến dịch từ thiện)
  + Kết thúc đấu giá
  + Xuất file excels thông tin chiến dịch, thông tin đấu giá <br/>

## <h2 id="giaodien">5. Giao diện</h2>

  <h3><i>User</i></h3>
  <h4>&emsp;&emsp;&emsp; --- Landing Page ---</h4>
      <img src="https://user-images.githubusercontent.com/82920615/221351827-c376935e-eee3-42ac-8b94-2de1ed9bc83d.png" style="width:700px ; height:980px"/>
  <br/>
  
  
   <h4>&emsp;&emsp;&emsp; --- Account ---</h4>
      <img src="https://user-images.githubusercontent.com/82920615/221353527-b480deae-d4e4-4d51-a1c1-7d3fec508dd5.png" style="width:700px ; height:770px"/>
  <br />
  
  <h4>&emsp;&emsp;&emsp; --- Auction ---</h4>
      <img src="https://user-images.githubusercontent.com/82920615/221362038-8dc2c2f1-98b6-498d-bf49-12f37612edf0.png" style="width:700px ; height:550px"/>
  <br />
      <img src="https://user-images.githubusercontent.com/82920615/221362013-7b3dce48-b3e1-4a9d-b1c0-5cc51b399a09.png" style="width:700px ; height:350px"/>
  <br />  

    
   <h4>&emsp;&emsp;&emsp; --- Create NFT ---</h4>
      <img src="https://user-images.githubusercontent.com/82920615/221353911-bf88913b-ecec-45cf-a19a-de2db3a32305.png" style="width:700px ; height:320px"/>
  <br />
  
  <h4>&emsp;&emsp;&emsp; --- History ---</h4>
      <img src="https://user-images.githubusercontent.com/82920615/221362091-a74eb443-68f4-4bd2-8fb0-fa2bba8ad78c.png" style="width:700px ; height:320px"/>
  <br />
   <h4>&emsp;&emsp;&emsp; --- Etherscan(history detail) ---</h4>
      <img src="https://user-images.githubusercontent.com/82920615/221354225-78de3220-3286-4872-b7f6-83439b0c3e5f.png" style="width:700px ; height:320px"/>
  <br />


  
<h3><i>Admin</i></h3>
  <h4>&emsp;&emsp;&emsp; --- Landing page ---</h4>
        <img src="https://user-images.githubusercontent.com/82920615/221354323-8f20110d-04b2-4fe2-a1e5-192a0d07a297.png" style="width:700px ; height:900px"/>
   <br/>
  <h4>&emsp;&emsp;&emsp; --- Manage NFT ---</h4>
        <img src="https://user-images.githubusercontent.com/82920615/221354429-7808abc5-1ad9-42c9-af26-a565d9fd0d68.png" style="width:700px ; height:400px"/>
   <br/>
  <h4>&emsp;&emsp;&emsp; --- Manage Campaign ---</h4>
        <img src="https://user-images.githubusercontent.com/82920615/221354489-77fabdb6-864a-425b-871c-27006fb19cc1.png" style="width:700px ; height:320px"/>
   <br/>
  <h4>&emsp;&emsp;&emsp; --- List Auction ---</h4>
        <img src="https://user-images.githubusercontent.com/82920615/221354513-08f75dbb-f9d3-4e35-a9c0-86e3f154b16d.png" style="width:700px ; height:320px"/>
   <br/>
  <h4>&emsp;&emsp;&emsp; --- Create Auction ---</h4>
        <img src="https://user-images.githubusercontent.com/82920615/221354584-1fc6caa3-2dac-45f8-885d-cb94122e4407.png" style="width:700px ; height:320px"/>
        <br/>
        <img src="https://user-images.githubusercontent.com/82920615/221354639-ff0056fb-4c7b-4598-b2b9-994dca301328.png" style="width:700px ; height:320px"/>
  
  <h4>&emsp;&emsp;&emsp; --- End Auction ---</h4>
        <img src="https://user-images.githubusercontent.com/82920615/221354699-a58d830f-6563-40e8-bda3-4692f1a4494b.png" style="width:700px ; height:400px"/>
   <br/>




