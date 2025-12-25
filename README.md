# PTDL_Benh_Tim
<h1>Dựa trên các bước đã thực hiện:

Số cụm tối ưu: Dựa trên biểu đồ Silhouette Score, số cụm tối ưu được chọn là 7.
Điểm Silhouette cuối cùng: Mô hình K-Means với 7 cụm đạt được điểm Silhouette là 0.14139725419649787. Điểm này, mặc dù dương, nhưng tương đối thấp. Điều này cho thấy rằng các cụm được hình thành không quá rõ ràng hoặc có thể có sự chồng chéo đáng kể giữa chúng. Một điểm Silhouette cao hơn (gần 1) sẽ chỉ ra các cụm được phân tách tốt hơn.
Biểu đồ phân cụm KMeans (PCA): Biểu đồ này hiển thị dữ liệu của bạn được chiếu xuống hai thành phần chính của PCA và được tô màu theo cụm mà chúng được gán. Với điểm Silhouette tương đối thấp, có khả năng bạn sẽ thấy các cụm hơi trộn lẫn trên biểu đồ chứ không phải là những nhóm riêng biệt rõ ràng. Điều này phù hợp với việc các cụm không có ranh giới rõ ràng.
Nhìn chung, kết quả cho thấy mô hình K-Means đã phân chia dữ liệu thành 7 cụm, nhưng chất lượng phân cụm (đo bằng Silhouette Score) không cao lắm, gợi ý rằng có thể các cụm trong dữ liệu không được tách biệt rõ ràng dựa trên các đặc trưng hiện có.

</h1>
