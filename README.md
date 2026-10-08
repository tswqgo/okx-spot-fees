# phí spot OKX: Cách tính maker, taker, bảng phí VIP và cách giảm chi phí giao dịch

Khi tìm “phí spot OKX”, phần lớn người dùng muốn biết ba điều: giao dịch mua bán crypto mất bao nhiêu, lệnh market và limit có mức phí khác nhau không, và làm thế nào để giảm chi phí sau khi mở tài khoản.

Câu trả lời ngắn gọn là: **OKX không áp dụng một mức phí spot duy nhất cho mọi lệnh**. Chi phí phụ thuộc vào cấp tài khoản, loại cặp giao dịch, cách lệnh được khớp và đôi khi là trạng thái tài khoản phái sinh. Với người dùng thông thường, mức phí tham chiếu phổ biến trên thị trường spot là **0,08% maker và 0,10% taker** đối với các cặp thuộc nhóm tiêu chuẩn. Tuy nhiên, một số cặp có thể có mức phí riêng hoặc được miễn phí theo thông báo của OKX.

Bài viết này tổng hợp cách tính phí spot OKX, toàn bộ các bậc VIP đang được công bố, ví dụ thực tế và cách kiểm tra mức phí áp dụng đúng cho tài khoản của bạn.

> Mức phí hiển thị sau khi đăng nhập mới là mức dùng để tính cho tài khoản cụ thể. Bảng công khai có thể chỉ là mức tham khảo và OKX có thể điều chỉnh nhóm giao dịch theo từng thời điểm hoặc khu vực.

## Phí spot OKX là gì?

Giao dịch spot là hình thức mua hoặc bán trực tiếp một tài sản crypto trên sổ lệnh. Ví dụ:

- Mua BTC bằng USDT qua cặp BTC-USDT.
- Bán ETH lấy USDT qua cặp ETH-USDT.
- Mua SOL bằng USDC qua cặp SOL-USDC.
- Giao dịch một token với BTC, ETH hoặc stablecoin khác.

Phí spot được tính khi lệnh được khớp. Nếu lệnh chưa khớp hoặc bị hủy trước khi khớp, phần chưa khớp không bị tính phí. Công thức cơ bản là:

text
Phí giao dịch = Tỷ lệ phí × khối lượng tài sản được khớp


Khi mua crypto, phí thường được trừ vào lượng crypto nhận được. Khi bán, phí thường được khấu trừ từ số tiền thu về. Vì vậy, số lượng bạn đặt mua và số lượng thực tế nhận được có thể chênh lệch nhẹ sau khi trừ phí.

Ví dụ, bạn mua 1.000 USDT Bitcoin với mức phí taker 0,10%. Phí quy đổi theo giá trị lệnh là khoảng:

text
1.000 × 0,10% = 1 USDT


Bạn không mất 1 USDT dưới dạng một khoản thanh toán riêng. Hệ thống sẽ khấu trừ phí trực tiếp trong giao dịch, tùy theo hướng mua hoặc bán và loại tài sản được giao dịch.

## Maker và taker khác nhau thế nào?

Hai khái niệm này thường gây nhầm lẫn vì chúng không hoàn toàn đồng nghĩa với “lệnh limit” và “lệnh market”.

### Maker

Maker là lệnh bổ sung thanh khoản cho sổ lệnh. Lệnh được đặt trên sổ lệnh và chờ một lệnh khác khớp vào. Trong nhiều trường hợp, lệnh limit không khớp ngay sẽ được tính là maker.

Ví dụ:

- BTC đang có giá bán thấp nhất là 60.000 USDT.
- Bạn đặt lệnh mua BTC ở 59.800 USDT.
- Lệnh chưa khớp ngay và nằm chờ trên sổ lệnh.
- Khi có người bán vào mức giá đó, lệnh của bạn được khớp với tư cách maker.

Mức phí maker thường thấp hơn taker vì bạn đang cung cấp thanh khoản cho thị trường.

### Taker

Taker là lệnh lấy thanh khoản có sẵn trên sổ lệnh. Lệnh được khớp ngay với các lệnh đang chờ thường bị tính phí taker.

Ví dụ:

- BTC đang có lệnh bán ở mức 60.000 USDT.
- Bạn đặt lệnh market mua BTC.
- Lệnh được khớp ngay với các lệnh bán hiện có.
- Giao dịch được tính theo mức phí taker.

Lệnh market thường là taker, nhưng đây không phải quy tắc tuyệt đối duy nhất. Một lệnh limit cũng có thể bị tính là taker nếu mức giá đặt vào khiến nó khớp ngay với lệnh đang có trên sổ lệnh. OKX xác định maker hay taker dựa trên **cách lệnh thực sự được khớp**, không chỉ dựa vào tên loại lệnh.

## Bảng phí spot OKX theo từng cấp VIP

Khung phí toàn cầu của OKX chia người dùng thành nhóm thông thường và VIP 1 đến VIP 9. Cấp tài khoản được xác định dựa trên tài sản nắm giữ hoặc khối lượng giao dịch trong 30 ngày. Chỉ cần đạt một trong hai điều kiện là có thể được xét cấp tương ứng.

Bảng dưới đây dùng mức tham chiếu cho **nhóm 1, nhóm 2 và nhóm 3** trên thị trường spot. Đây là các nhóm phí tiêu chuẩn được OKX công bố. Một số cặp đặc biệt có thể áp dụng bảng khác.

| Cấp tài khoản | Điều kiện tài sản hoặc khối lượng 30 ngày | Phí maker | Phí taker | Cặp miễn phí | Liên kết đăng ký |
| --- | ---: | ---: | ---: | --- | --- |
| Người dùng thông thường | Tài sản dưới 100.000 USD hoặc khối lượng dưới 1.000.000 USD | 0,0800% | 0,1000% | 0% / 0% ở các cặp đủ điều kiện | [ Đăng ký OKX và kiểm tra phí áp dụng](https://okx.com/join/CASH20) |
| VIP 1 | Tài sản từ 100.000 USD hoặc khối lượng từ 1.000.000 USD | 0,0675% | 0,0800% | 0% / 0% ở các cặp đủ điều kiện | [ Xem điều kiện VIP 1](https://okx.com/join/CASH20) |
| VIP 2 | Tài sản từ 250.000 USD hoặc khối lượng từ 5.000.000 USD | 0,0600% | 0,0700% | 0% / 0% ở các cặp đủ điều kiện | [ Mở tài khoản với mã giới thiệu](https://okx.com/join/CASH20) |
| VIP 3 | Tài sản từ 500.000 USD hoặc khối lượng từ 10.000.000 USD | 0,0550% | 0,0650% | 0% / 0% ở các cặp đủ điều kiện | [ Kiểm tra tài khoản giao dịch OKX](https://okx.com/join/CASH20) |
| VIP 4 | Tài sản từ 2.000.000 USD hoặc khối lượng từ 20.000.000 USD | 0,0300% | 0,0450% | 0% / 0% ở các cặp đủ điều kiện | [ Xem lựa chọn tài khoản OKX](https://okx.com/join/CASH20) |
| VIP 5 | Tài sản từ 5.000.000 USD hoặc khối lượng từ 100.000.000 USD | 0,0250% | 0,0350% | 0% / 0% ở các cặp đủ điều kiện | [ Đăng ký để theo dõi cấp phí](https://okx.com/join/CASH20) |
| VIP 6 | Tài sản từ 10.000.000 USD hoặc khối lượng từ 200.000.000 USD | 0,0000% | 0,0300% | 0% / 0% ở các cặp đủ điều kiện | [ Truy cập OKX qua liên kết giới thiệu](https://okx.com/join/CASH20) |
| VIP 7 | Khối lượng giao dịch từ 500.000.000 USD | -0,0020% | 0,0250% | 0% / 0% ở các cặp đủ điều kiện | [ Kiểm tra chương trình phí OKX](https://okx.com/join/CASH20) |
| VIP 8 | Khối lượng giao dịch từ 1.000.000.000 USD | -0,0050% | 0,0200% | 0% / 0% ở các cặp đủ điều kiện | [ Mở tài khoản OKX](https://okx.com/join/CASH20) |
| VIP 9 | Khối lượng giao dịch từ 5.000.000.000 USD | -0,0075% | 0,0175% | 0% / 0% ở các cặp đủ điều kiện | [ Xem thông tin phí và VIP](https://okx.com/join/CASH20) |

Mức maker âm ở VIP 7, VIP 8 và VIP 9 có nghĩa là người dùng có thể nhận rebate maker theo chính sách tương ứng, nhưng điều kiện áp dụng thực tế còn phụ thuộc vào nhóm cặp, khu vực, loại tài khoản và chính sách tại thời điểm giao dịch. Không nên hiểu rằng mọi giao dịch đều chắc chắn được hoàn tiền.

Các cấp VIP cao cũng yêu cầu khối lượng rất lớn. Với nhà đầu tư cá nhân giao dịch vài trăm hoặc vài nghìn USD mỗi tháng, việc cố tăng khối lượng chỉ để giảm phí thường không hợp lý. Phí thấp hơn không bù được thua lỗ nếu bạn mở lệnh quá nhiều hoặc giao dịch khi chưa có kế hoạch.

## Phí theo nhóm cặp giao dịch

OKX chia các cặp spot thành ba nhóm chính:

- **Nhóm 1:** 10 cặp hàng đầu.
- **Nhóm 2:** Các cặp có hoạt động giao dịch trung bình và thanh khoản đáng kể.
- **Nhóm 3:** Các cặp còn lại trên thị trường spot.

Trong khung phí toàn cầu được OKX công bố, người dùng thông thường có mức 0,08% maker và 0,10% taker cho cả ba nhóm tiêu chuẩn. Tuy nhiên, từ VIP 4 trở lên, một số cấp có thể có chênh lệch giữa các nhóm. Ví dụ, ở VIP 4, phí taker của nhóm 1 là 0,045%, nhóm 2 là 0,050% và nhóm 3 là 0,055%.

Nhóm 1 gồm các cặp như:

- ADA-USDT
- BTC-USDT
- DOGE-USDT
- ETH-USDT
- PEPE-USDT
- SOL-USDT
- SUI-USDT
- XRP-USDT

Danh sách cặp có thể thay đổi. OKX cho biết nhóm ký hiệu và mức phí trên thị trường spot có thể được rà soát định kỳ để phù hợp với điều kiện thị trường. Một cặp đang thuộc nhóm phí này hôm nay có thể được phân loại lại sau đó.

## Cặp spot nào có thể được miễn phí?

Trong thông báo khung phí toàn cầu, OKX liệt kê một số cặp không mất phí, gồm:

- DAI-USDT
- PYUSD-USDT
- USDC-USDT
- USDG-USDT
- USDT-USD

Các cặp này được công bố với phí maker và taker bằng 0% trong bảng tương ứng. Tuy nhiên, không nên suy rộng rằng mọi giao dịch stablecoin trên OKX đều miễn phí. Chỉ những cặp và điều kiện được hiển thị là đủ điều kiện mới áp dụng mức 0%.

Ngoài ra, cặp **USDT-TRY** được ghi nhận là cặp có quy tắc đặc biệt và khả dụng theo khu vực. Một số cặp cũng có thể không mở cho mọi người dùng do giới hạn sản phẩm hoặc quy định tại từng quốc gia.

Đây là điểm nên kiểm tra trước khi đặt lệnh. Đừng chỉ nhìn vào tên token hoặc loại stablecoin. Hãy xem chính xác cặp giao dịch, mức maker và taker đang hiển thị trên màn hình đặt lệnh.

## Cách tính phí spot OKX qua ví dụ

### Ví dụ 1: Mua bằng lệnh market

Giả sử bạn mua BTC trị giá 2.000 USDT bằng lệnh market. Tài khoản đang ở cấp người dùng thông thường, phí taker là 0,10%.

text
Phí ước tính = 2.000 × 0,10% = 2 USDT


Số BTC nhận được sẽ tương ứng với giá khớp thực tế sau khi trừ phí. Nếu lệnh được chia thành nhiều lần khớp, phí được tính theo từng lần khớp rồi cộng lại.

### Ví dụ 2: Đặt lệnh limit nhưng vẫn bị tính taker

Bạn đặt lệnh limit mua BTC ở mức giá đang có sẵn trên sổ lệnh bán. Lệnh được khớp ngay. Dù chọn limit, lệnh này vẫn có thể bị tính taker vì nó lấy thanh khoản có sẵn.

Đây là lý do chỉ nhìn vào nút “Limit” chưa đủ để biết chắc mức phí.

### Ví dụ 3: Lệnh limit được tính maker

Bạn đặt lệnh mua thấp hơn giá bán hiện tại. Lệnh nằm chờ trên sổ lệnh và được khớp sau đó khi thị trường di chuyển về mức giá của bạn. Trong trường hợp này, giao dịch có thể được tính maker.

Tuy nhiên, nếu một phần lệnh khớp ngay và phần còn lại nằm chờ, một lệnh duy nhất có thể phát sinh cả phần maker lẫn taker. Lịch sử lệnh mới cho thấy chính xác từng phần đã được tính như thế nào.

## Cách kiểm tra phí thực tế trước khi giao dịch

OKX cho phép xem phí của tài khoản trong khu vực quản lý giao dịch. Trên website, bạn có thể vào phần tài sản và mở mục phí giao dịch của tôi. Trên ứng dụng, đường dẫn thường nằm trong khu vực hồ sơ hoặc cài đặt tài khoản.

Trước khi đặt lệnh, hãy kiểm tra:

1. Cấp phí hiện tại của tài khoản.
2. Cặp giao dịch đang chọn.
3. Phí maker.
4. Phí taker.
5. Khối lượng giao dịch spot trong 30 ngày.
6. Tài sản đang được tính để xét VIP.
7. Cặp đó có thuộc nhóm miễn phí hoặc nhóm đặc biệt không.

Trong giao diện đặt lệnh, OKX cũng hiển thị mức phí hiện hành của cặp giao dịch. Con số cuối cùng có thể khác ước tính ban đầu nếu lệnh được khớp nhiều phần, khớp theo mức giá khác nhau hoặc chuyển từ trạng thái maker sang taker.

Sau khi giao dịch hoàn tất, bạn có thể mở lịch sử lệnh, vào phần chi tiết từng lần khớp và xem dòng phí. Đây là dữ liệu đáng tin cậy nhất để đối chiếu, đặc biệt khi bạn đang dùng bot, lệnh chia nhỏ hoặc giao dịch với nhiều mức giá.

## Giao dịch Convert có giống giao dịch spot không?

Không hoàn toàn.

Giao dịch trên sổ lệnh spot thường hiển thị maker và taker riêng. Trong khi đó, các luồng mua bán nhanh hoặc Convert thường báo một mức giá tổng hợp. Chi phí có thể đã được tính vào mức giá được báo thay vì hiển thị như một dòng phí giao dịch riêng.

Điều này khiến nhiều người nghĩ Convert “không mất phí”. Thực tế, “không có dòng phí riêng” không đồng nghĩa với việc giá chuyển đổi chắc chắn giống giá tốt nhất trên sổ lệnh. Trước khi chuyển đổi số tiền lớn, nên so sánh:

- Giá mua hoặc bán được báo.
- Giá tham chiếu trên sổ lệnh.
- Chênh lệch giữa giá mua và giá bán.
- Số lượng tài sản thực tế nhận được.
- Phí mạng hoặc chi phí rút nếu bạn chuyển tài sản ra ngoài.

Nếu bạn chỉ muốn đổi một lượng nhỏ để thao tác nhanh, Convert có thể thuận tiện. Nếu bạn quan tâm sát đến chi phí, sổ lệnh spot thường cho phép kiểm soát giá và loại lệnh rõ hơn.

## P2P có bị tính phí spot không?

P2P là một cơ chế khác với giao dịch spot trên sổ lệnh. OKX cho biết giao dịch P2P không tính phí giao dịch theo cách của spot và khối lượng P2P cũng không được tính vào khối lượng giao dịch 30 ngày để xét cấp phí.

Tuy vậy, P2P vẫn có thể phát sinh các yếu tố chi phí khác:

- Chênh lệch giá giữa người mua và người bán.
- Phí ngân hàng hoặc ví thanh toán.
- Giới hạn phương thức thanh toán.
- Thời gian xử lý giao dịch.
- Rủi ro từ việc chuyển khoản sai nội dung hoặc không tuân thủ hướng dẫn.

Vì vậy, không nên so sánh “P2P miễn phí” với “spot mất 0,10%” rồi kết luận ngay rằng P2P luôn rẻ hơn. Hãy so sánh số tiền thực tế bạn phải trả và số tài sản nhận được.

## Cách giảm phí spot OKX hợp lý

### Dùng lệnh limit khi chiến lược cho phép

Nếu không cần khớp ngay, lệnh limit có thể giúp bạn trở thành maker và hưởng mức phí thấp hơn. Nhưng phải kiểm tra trạng thái khớp thực tế. Lệnh limit khớp ngay vẫn có thể bị tính taker.

Không nên đặt limit chỉ để “né phí” nếu giá thị trường đang biến động nhanh. Lệnh có thể không khớp, trong khi giá đi xa khỏi mức bạn mong muốn.

### Theo dõi đúng cấp VIP

Cấp phí được tính dựa trên tài sản và khối lượng giao dịch trong 30 ngày. OKX chụp dữ liệu định kỳ và cập nhật cấp phí theo lịch hệ thống, không phải ngay lập tức sau từng giao dịch. Theo tài liệu hỗ trợ, dữ liệu được chụp vào 00:00 UTC+8 và cấp phí thường được cập nhật trong khoảng 04:00 đến 06:00 UTC+8.

Nếu bạn vừa đạt điều kiện VIP nhưng chưa thấy mức phí thay đổi, có thể hệ thống chưa hoàn tất chu kỳ cập nhật. Hãy kiểm tra lại sau thời gian cập nhật hoặc xem trực tiếp trong mục phí của tài khoản.

### Kiểm tra nhóm cặp trước khi giao dịch

Với cấp VIP cao, chênh lệch giữa nhóm 1, nhóm 2 và nhóm 3 có thể đáng kể. Nếu bạn giao dịch thường xuyên, hãy kiểm tra phí của chính cặp đang chọn thay vì chỉ nhớ một mức phí chung của OKX.

### Không nhầm phí giao dịch với phí rút

Phí spot chỉ là phí khi lệnh mua bán được khớp. Nạp tiền, rút crypto, thanh toán bằng thẻ, chuyển mạng lưới hoặc sử dụng một số sản phẩm khác có thể có chi phí riêng. OKX cũng lưu ý rằng phí nạp, rút và giao dịch thẻ không nằm trong cùng nhóm với phí giao dịch trên sổ lệnh.

Một giao dịch có thể có các khoản liên quan khác:

- Phí spot khi mua hoặc bán.
- Phí rút tài sản.
- Phí mạng blockchain.
- Phí ngân hàng hoặc nhà cung cấp thanh toán.
- Chênh lệch giá trong Convert hoặc mua nhanh.

Khi tính chi phí thực tế, hãy cộng toàn bộ các khoản này thay vì chỉ nhìn vào phần trăm maker hoặc taker.

## Mã giới thiệu CASH20 có tác dụng gì?

Liên kết đăng ký được cung cấp trong bài viết là liên kết giới thiệu OKX kèm mã **CASH20**. Thông tin đi kèm cho biết chương trình có mức hoàn phí 20%, nhưng điều kiện, thời hạn, khu vực áp dụng và số tiền hoàn thực tế cần được kiểm tra trực tiếp trên trang đăng ký hoặc trong tài khoản sau khi mở tài khoản.

Bạn có thể bắt đầu tại đây:

[👉 Đăng ký OKX bằng mã CASH20](https://okx.com/join/CASH20)

Khi đăng ký, nên kiểm tra các điểm sau:

1. Mã giới thiệu đã được tự động ghi nhận hay chưa.
2. Tỷ lệ hoàn phí được hiển thị ở trang chương trình.
3. Thời gian áp dụng chương trình.
4. Loại giao dịch được tính hoàn phí.
5. Mức hoàn tối đa nếu có.
6. Điều kiện xác minh danh tính hoặc khối lượng giao dịch.
7. Thời gian trả phần hoàn phí.

Hoàn phí từ chương trình giới thiệu không đồng nghĩa với việc phí giao dịch gốc bị xóa. Thông thường, hệ thống vẫn ghi nhận phí theo cấp tài khoản và sau đó xử lý phần thưởng hoặc hoàn phí theo điều kiện chương trình. Vì vậy, hãy lưu lại lịch sử giao dịch và lịch sử phần thưởng để đối chiếu.

## Nên chọn OKX nếu bạn giao dịch spot ở mức nào?

Với người mới, mức phí quan trọng nhưng không phải yếu tố duy nhất. Nếu mỗi tháng bạn chỉ mua một vài lần và nắm giữ dài hạn, chênh lệch vài phần trăm của một phần nghìn thường nhỏ hơn tác động của biến động giá. Việc chọn sai cặp, mua nhầm giá hoặc trả phí rút cao có thể ảnh hưởng nhiều hơn.

Nếu bạn giao dịch thường xuyên, các yếu tố đáng quan tâm hơn gồm:

- Tỷ lệ maker và taker thực tế.
- Thanh khoản của cặp giao dịch.
- Độ sâu sổ lệnh.
- Chênh lệch giá mua bán.
- Phí rút của từng mạng lưới.
- Khả năng theo dõi lịch sử khớp lệnh.
- Điều kiện nâng cấp VIP.
- Các chương trình hoàn phí đang còn hiệu lực.

Mức tham chiếu 0,08% maker và 0,10% taker phù hợp để ước tính nhanh cho người dùng thông thường. Nhưng trước khi đặt lệnh, hãy mở bảng phí trong tài khoản và kiểm tra trực tiếp cặp bạn định giao dịch. Đó mới là con số cần dùng để tính chi phí thật.

[👉 Kiểm tra phí spot và bắt đầu giao dịch trên OKX](https://okx.com/join/CASH20)

## Kết luận

Phí spot OKX được quyết định bởi cấp VIP, loại cặp giao dịch và cách lệnh được khớp. Người dùng thông thường thường gặp mức **0,08% maker và 0,10% taker** ở các nhóm cặp tiêu chuẩn. Lệnh market thường là taker, còn lệnh limit có thể là maker hoặc taker tùy cách khớp thực tế.

Nếu muốn giảm chi phí, hãy:

- Kiểm tra phí trực tiếp sau khi đăng nhập.
- Phân biệt maker với taker.
- So sánh giá spot với Convert.
- Xem nhóm phí của từng cặp.
- Theo dõi khối lượng 30 ngày và cấp VIP.
- Tách phí giao dịch khỏi phí rút và phí thanh toán.
- Kiểm tra điều kiện của mã CASH20 trước khi giao dịch.

Phí thấp chỉ có ý nghĩa khi bạn vẫn kiểm soát được giá khớp, khối lượng và rủi ro. Giao dịch nhiều hơn để săn cấp VIP không phải lúc nào cũng giúp tiết kiệm.
