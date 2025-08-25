<?php
// CẤU TRÚC ĐIỀU KHIỂN PHP

// 1. CÂU LỆNH ĐIỀU KIỆN
echo "<h2>1. CÂU LỆNH ĐIỀU KIỆN</h2>";

// 1.1. if
echo "<h3>1.1. if</h3>";
$age = 18;
if ($age >= 18) {
    echo "Bạn đủ tuổi để thi bằng lái xe.<br>";
}

// 1.2. if ... else
echo "<h3>1.2. if ... else</h3>";
$score = 45;
if ($score >= 50) {
    echo "Bạn đã đậu!<br>";
} else {
    echo "Bạn đã trượt!<br>";
}

// 1.3. if ... elseif ... else
echo "<h3>1.3. if ... elseif ... else</h3>";
$score = 85;
if ($score >= 90) {
    echo "Xuất sắc!<br>";
} elseif ($score >= 75) {
    echo "Giỏi!<br>";
} elseif ($score >= 50) {
    echo "Trung bình!<br>";
} else {
    echo "Yếu!<br>";
}

// 1.4. switch ... case
echo "<h3>1.4. switch ... case</h3>";
$day = 3;
switch ($day) {
    case 1:
        echo "Thứ Hai<br>";
        break;
    case 2:
        echo "Thứ Ba<br>";
        break;
    case 3:
        echo "Thứ Tư<br>";
        break;
    default:
        echo "Ngày không hợp lệ<br>";
}
echo "<hr>";

// 2. VÒNG LẶP
echo "<h2>2. VÒNG LẶP</h2>";

// 2.1. for
echo "<h3>2.1. Vòng lặp for</h3>";
for ($i = 1; $i <= 5; $i++) {
    echo "Lần lặp: $i <br>";
}

// 2.2. while
echo "<h3>2.2. Vòng lặp while</h3>";
$count = 1;
while ($count <= 5) {
    echo "Số: $count <br>";
    $count++;
}

// 2.3. do ... while
echo "<h3>2.3. Vòng lặp do...while</h3>";
$num = 1;
do {
    echo "Số: $num <br>";
    $num++;
} while ($num <= 3);

// 2.4. foreach
echo "<h3>2.4. Vòng lặp foreach</h3>";
$fruits = ["Táo", "Cam", "Nho"];
foreach ($fruits as $fruit) {
    echo "Trái cây: $fruit <br>";
}

echo "<hr>";
echo "<h2>Kết thúc ví dụ về cấu trúc điều khiển trong PHP!</h2>";
?>
