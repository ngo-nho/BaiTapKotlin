fun main(args: Array<String>) {

    val maSV = args[0]
    val hoTen = args[1].replace("_", " ")

    val math = args[2].toDouble()
    val programming = args[3].toDouble()
    val database = args[4].toDouble()

    // Tính tổng điểm
    val tongDiem = math + programming + database

    // Tính điểm trung bình
    val gpa = tongDiem / 3

    // Tìm điểm cao nhất
    val diemCaoNhat = maxOf(math, programming, database)

    // Kiểm tra sinh viên đạt
    val ketQua = if (gpa >= 5.0) {
        "Đạt"
    } else {
        "Không đạt"
    }

    // In kết quả
    println("===== THÔNG TIN SINH VIÊN =====")
    println("Mã sinh viên: $maSV")
    println("Họ tên: $hoTen")

    println()
    println("===== KẾT QUẢ =====")
    println("Tổng điểm: $tongDiem")
    println("Điểm trung bình: %.2f".format(gpa))
    println("Điểm cao nhất: $diemCaoNhat")
    println("Sinh viên có đạt không: $ketQua")
}
