#quản lí thông tin version 1 

### cài đặt :
	1. Cài database mẫu  :


```

			-- phpMyAdmin SQL Dump
-- version 4.5.5.1deb2.trusty~ppa.1
-- http://www.phpmyadmin.net
--
-- Host: localhost
-- Generation Time: Apr 04, 2016 at 10:11 AM
-- Server version: 5.5.47-0ubuntu0.14.04.1
-- PHP Version: 5.6.19-1+deb.sury.org~trusty+1

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `quanlithongtin`
--

-- --------------------------------------------------------

--
-- Table structure for table `thong_tin`
--

CREATE TABLE `thong_tin` (
  `id` bigint(20) NOT NULL,
  `sdt` varchar(20) COLLATE utf8_unicode_ci NOT NULL,
  `dau_so` varchar(8) COLLATE utf8_unicode_ci NOT NULL,
  `thoi_gian` varchar(60) COLLATE utf8_unicode_ci NOT NULL,
  `noi_dung` text COLLATE utf8_unicode_ci NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;

--
-- Dumping data for table `thong_tin`
--

INSERT INTO `thong_tin` (`id`, `sdt`, `dau_so`, `thoi_gian`, `noi_dung`) VALUES
(2372, '84944753976', '8189', '08-Nov-2015 05:37:58', 'Caukt'),
(2373, '84919213184', '7053', '08-Nov-2015 06:18:36', 'Xshg'),
(2374, '84919235408', '1554', '08-Nov-2015 06:18:40', 'Huy');

--
-- Indexes for dumped tables
--

--
-- Indexes for table `thong_tin`
--
ALTER TABLE `thong_tin`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT for dumped tables
--

--
-- AUTO_INCREMENT for table `thong_tin`
--
ALTER TABLE `thong_tin`
  MODIFY `id` bigint(20) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=2396;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;


```

	2.Config mật khẩu và tên tài khoản MySql  `dbpoolname.user` và `dbpoolname.password` 
	
	3.Sử dụng sampleData.txt để nhập thử dữ liệu 
