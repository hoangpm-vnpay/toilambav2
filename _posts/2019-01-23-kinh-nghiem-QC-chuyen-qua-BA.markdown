---
layout: post
title:  Kinh nghiệm chuyển từ Quality Control sang Business Analyst
date: 2019-04-19 12:00:20 +0700
description: Chia sẻ kinh nghiệm để chuyển từ Quality Control qua Business Analyst. Mình phân làm 2 đối tượng. Đối tượng thứ nhất là chưa tìm hiểu gì về BA thì nên apply QC để hiểu về quy trình, cách làm việc trong team, một số kỹ năng về document sau đó mình làm BA tốt hơn. # Add post description (optional)
image: img/qc-to-ba.png # Add image post (optional)
tags: Testing, BA, Business Analyst]
---
## Mục lục
*  Auto generated table of contents
{:toc}

## 1. Giới thiệu
Hoàng Phan là bạn đại học của mình, hiện tại Hoàng đang là Business Analyst tại Kyanon Digital (2018-2019). Thực ra gọi là phỏng vấn nhưng đây cũng như buổi nói chuyện bình thường giữa mình với Hoàng thôi. Trong buổi nói chuyện còn có [Linh Nguyễn](https://niviki.com/phong-van-ky-su-qc/){:target="_blank"} nữa.

## 2. Nội dung

**Khoa**: Hoàng có thể giới thiệu bản thân với bạn đọc trên NIVIKI.COM được không?

**Hoàng**: Chào mọi người, mình là Hoàng hiện tại mình đang làm ở vị trí BA trong khoảng thời gian 6 tháng. Hết rồi :D

**Khoa**: BA là công việc đầu tiên của Hoàng hay là trước đó Hoàng có làm gì không?

**Hoàng**: Trước đó mình có làm ở vị trí Quality Control (QC) khoảng 8 tháng, và có một thời gian mình làm freelance ở mảng frontend.

**Khoa**: Được biết Hoàng là Đội Trưởng đội Công tác Xã hội UIT có đúng không? Vậy thì kinh nghiệm làm Đội Trưởng đội Công tác Xã hội UIT có giúp ích gì cho công việc QC không?

**Hoàng**: Mình thấy rằng việc rèn luyện kỹ năng mềm, tham gia các tổ chức sự kiện thì nó giúp cho mình tự tin, trình bày nội dung rõ ràng và dễ hiểu hơn. Trước đó mình nói thì nó hơi bị vòng vòng. Sau khi mình tham gia các hoạt động dự án tình nguyện thì mình làm quen với việc trình bày nội dung của các buổi tình nguyện đến cho Tình Nguyện viên, chính quyền địa phương và từ đó dẫn đến khi đi làm mình cũng làm tốt làm việc ở QC và cả BA. Khi gặp khách hàng, dễ nói chuyện hơn, mình trao đổi với các thành viên trong team của mình như là dev, designer cũng sẽ tốt hơn.

![Hoang]({{site.baseurl}}/images/img/qc-to-ba/Hoang-tinh-nguyen.jpg)
*Hoàng trong một buổi tổ chức hoạt động tình nguyện - Người quản trò đang cầm micro*

**Khoa**: Hoàng có thể mô tả sơ sơ QC là làm gì không?

**Hoàng**: QC là đảm bảo cái mà dev làm ra chạy đúng requirement của khách hàng. Đảm bảo cho phần mềm chạy tốt hơn không có quá nhiều lỗi (phần mềm nào chẳng có lỗi :D).

**Khoa**: Phần mềm phải làm xong rồi mới kiểm tra lại hay là?

**Hoàng**: Thực ra thì dựa vào requirement, mình xây dựng ra những bộ test case

**Khoa**: Là viết test case trước khi dev làm

**Hoàng**: Không, cùng lúc với dev làm.

**Khoa**: Công việc đó (QC) Hoàng làm khoảng 8 tháng xong rồi nghỉ thì tại sao lại không tiếp tục công việc đó?

**Hoàng**: Thứ nhất là công ty quá xa vị trí mình ở. Thứ hai là ở trường mình có nhiều bài tập đồ án tốn khá nhiều thời gian cho nên mình không đảm bảo được thời gian để đi làm. Mình cũng đang muốn công việc của mình nó thiên về giao tiếp với khách hàng nhiều hơn nên mình quyết định nghỉ một thời gian để tìm hiểu về vị trí BA

**Khoa**: Vậy là QC sẽ không có nói chuyện gì với khách hàng đúng không?

**Hoàng**: Cũng có nhưng mà nó ít so với BA

**Khoa**: Ủa, vậy sẽ nói chuyện gì với khách hàng

**Hoàng**: Thường khách hàng sẽ hỏi là quy trình kiểm thử như thế nào? Sử dụng tool gì để test. Khách hàng có thể track bug ở đâu, trao đổi về Report Testing.

**Khoa**: Có khi nào khách hàng tự báo bug luôn không?

**Hoàng**: Có. Tất nhiên là sẽ không có phần mềm nào hoàn chỉnh 100%, sẽ luôn có bug. Thì khi khách hàng gặp Bug có thể đăng bug lên, QC có thể cùng trao đổi khách hàng: bug đó thỉnh thoảng bị hay là hay là luôn luôn xảy ra. Hay là do yếu tố bên khách hàng như mạng internet, thiết bị.

**Khoa**: Vậy là QC sẽ là người tìm ra nguyên nhân lỗi chứ không phải dev hả?

**Hoàng**: QC sẽ vào cái bug đó và làm lại xem có gặp bug đó hay không, gọi là reproduce Bug. Sau đó, QC sẽ liên hệ với dev để coi thử là bug đó có có thực sự là do dev hay là do vấn đề nào khác.

**Khoa**: Còn trường hợp cái bug đó không được không làm lại được?

**Hoàng**: Ừ thì mình cũng có một trải nghiệm như sau. Có một cái lỗi mà 7 người trong team mình đều không reproduce lại được. Thì mình có trao đổi với khách hàng là cứ để cái bug đó ở trong backlog. Một thời gian thì sau khoảng 2, 3 sprint thì cũng không gặp lại nó.

**Khoa**: Hoàng có nói là Hoàng thích làm BA vì được nói chuyện nhiều với khách hàng thì từ đâu mà mày có suy nghĩ như vậy. Tức là Hoàng tìm hiểu công việc BA ở đâu để quyết định chuyển công việc như thế?

**Hoàng**: Đầu tiên mình được bạn Khoa giới thiệu, sao không thử mảng BA đi. Vì Khoa biết mình làm Công tác Xã hội thì đi Khoa nghĩ là BA cũng hợp với mình.

{% highlight markdown %}
Khúc này hơi deep tý nha mấy bạn, tại lỡ hỏi rồi. Thực chất thì công việc của Hoàng mình cũng hiểu phần nào rồi, chủ yếu để cho mọi người hiểu quá trình Hoàng làm việc ý mà. Thôi mọi người đọc tiếp nhé - Khoa.
{% endhighlight %}

Thực chất thì lúc đó cũng không biết 100% là hợp hay không nhưng mà mình đã quyết định bỏ thời gian ra tìm hiểu về vị trí này khoảng 3 tháng: Mình bắt đầu tìm hiểu là vị trí này công ty nào tuyển, tuyển có nhiều hay không,  range lương như thế nào.

Rồi mình đọc các job description thì mình mới coi là mình thiếu cái kỹ năng gì từ đó thì mình đi học những cái mình thiếu

**Khoa**: Vậy cái thiếu đó là gì?

**Hoàng**: Thứ nhất là UI/UX, nhưng mình lợi cái là có tham gia Công tác Xã hội, biết được design, một ít về UI/UX và từng tìm hiểu rồi.

**Khoa**: Design đó có kỹ không, hay cái mức độ như thế nào?

**Hoàng**: Như là vẽ wireframe thôi, thấy design nó hợp lý, thân thiện với người dùng, hợp lý về UX, còn không nhất thiết phải quá đẹp hay gì đó. Thường thì muốn đẹp thì vẽ wireframe, đề xuất xong designer sẽ thực hiện bản hoàn chỉnh hơn.

**Khoa**: Còn kỹ năng nào nữa không?

**Hoàng**: Thứ hai đó là kỹ năng sử dụng các tool vẽ use case như draw.io. Nó online free và tiện lợi, có thể export ra PNG, lưu xuống máy dạng XML rất tiện.

Cái này mình hay dùng để vẽ các User Case, biểu đồ khi làm đồ án ở Đại học. Ngoài ra mình còn biết thêm những tool khác như Visio của Microsoft, Lucidchart.

Kỹ năng nữa cũng rất quan trọng đó là kỹ năng giao tiếp. Mình giao tiếp tiếng Việt cũng ổn, thì mình sẽ làm việc tốt với các bên ở Internal team (Việt Nam Team). Nhưng khách hàng đa số là người nước ngoài nên mình cần phải improve thêm về Tiếng Anh. Hiện tại mình chat với khách cũng tốt, nhưng về phần giao tiếp (nói chuyện trực tiếp) tiếng Anh còn hơi kém.

Kỹ năng quản lý thì mình tham khảo thêm về cách sử dụng các tools như Jira, TFS, đọc nhiều tài liệu về quản lý dự án, quản lý task để có sẵn lý thuyết, khi đi làm mình áp dụng luôn, đỡ tốn thời gian tìm hiểu khi đi làm.

Và tham gia các group trên facebook, cộng đồng BA để đọc những bài viết, những kinh nghiệm những anh chị đi trước đã trải qua, và chia sẻ lại để improve khả năng phân tích và giải quyết vấn đề.

**Khoa**: Hoàng thấy kỹ năng nào của QC giúp ích được cho BA

**Hoàng**: Thứ nhất là trong BA có QC. Cái mà mình thấy hay dùng nhất của QC là UAT (User Acceptance Testing – Kiểm thử chấp nhận). Và có thêm các kỹ năng về document, tức là mình đã làm quen với việc đọc document, requirement và xây dựng các test case tỉ mĩ từ khi làm QC, nên qua áp dụng cho BA cũng tốt hơn.

**Khoa**: Ủa vậy Hoàng có thể nói kỹ hơn sự khác nhau giữa test casse và UAT

**Hoàng**: Test case là mình test chi tiết từng trường hợp hơn. Còn UAT là kiểm thử chấp nhận. Tức là mình kiểm tra những cái case người dùng sẽ hay dùng nhất, phần mềm có đáp ứng cho tiêu chí chấp nhận và có sẵn sàng cho sử dụng không. Mình thường thực hiện nó thông qua một check list, có những tính năng mà cần người dùng UAT nhiều, thì nhờ các anh chị trong công ty vô thử, và chạy thử với mỗi người 1 trường hợp khác nhau, và xin feedback từ họ. Trước UAT là QC đã đảm bảo phần mềm chạy tốt rồi và UAT mình test lại để cho một user dùng những tính năng hay dùng nó chấp nhận được là ổn.

**Khoa**: Tức là UAT mình có thể đưa cho khách hàng coi và họ hiểu được, đúng không?

**Hoàng**: Ừm, đúng rồi. Họ xem và hiểu thông qua checklist mình xây dựng.

**Khoa**: Còn test case nó thiên về kỹ thuật hơn?

**Hoàng**: Đúng rồi, test case đôi khi kiểm tra những trường hợp rất là lắc léo luôn.

**Khoa**: Thì công việc mới của Hoàng thì Hoàng apply như thế nào

**Hoàng**: Lúc mình đi làm thì đã có 8 tháng kinh nghiệm QC, nhưng mình chấp nhận apply vị trí intern 2 tháng.

Ban đầu mình làm ở BA dạng pre-sale. Đầu tiên mình tham gia phân tích các tool như CRM, HRM các tool về quản lý nhân sự, khách hàng. Sau đó dựa vào tuỳ yêu cầu của khách hàng để đề xuất giải các tool phù hợp hoặc xây dựng thêm tính năng theo mong muốn của khách hàng.

Sau đó mình đề xuất với sếp của mình xin chuyển sang IT BA và được sếp đồng ý chuyển sang dự án mới với vai trò IT BA sau 2 tháng intern.

**Khoa**: Thì dự án mới đó là dự án đã có sẵn?

**Hoàng**: Dự án đó đã có từ trước nhưng chạy chưa tốt, khách hàng muốn nâng cấp. Khách hang của dự án này bên Sing.

**Linh**: Khi join vào một dự án có sẵn như vậy thì việc học cái domain knowledge có khó không?

**Hoàng**: Thật ra thì may mắn là dự án này cũng liên quan đến tình nguyện xã hội luôn, mà mình đã có 3 năm sinh hoạt ở Đội Công tác Xã hội nên cũng có khá nhiều kinh nghiệm về thể loại, nên mình rất nhanh hiểu về domain này. Còn những tính năng thì cũng chưa quá phức tạp, nó dạng như blog, và chạy các chiến dịch liên quan đến việc truyền thông điệp.

**Linh**: Theo Hoàng thì làm việc với khách nước ngoài vậy có khó khăn gì không?

**Hoàng**: Theo mình nghĩ là tiếng Anh là điểm yếu nhất của mình. Đôi khi khách hiểm lầm ý mình, và cần phải vẽ sơ đồ để giải thích. Thứ hai là làm việc online với khách nên việc chờ đợi làm mình trĩ hoàn nhiều việc khác.

**Khoa**: Khó khăn với khách hàng là vậy, còn khó khăn với team dev, designer như thế nào?

**Hoàng**: Designer là bên team Singapore luôn, nên được coi như là trao đổi với khách hàng. Còn team Dev, QC thì hiện tại mình thấy chưa có khó khăn với bản thân trong dự án này, vì mình cũng có thời gian làm Dev và cả QC nữa, nên khi truyền đạt về requirement thì mình share theo hướng của Dev và QC luôn.

**Khoa**: Quy trình cho 1 tính năng mới thì như thế nào?

Quy trình hiện tại: Khách hàng sẽ đăng user story mô tả tính năng họ muốn làm ở đơn giản nhất. Và mình sẽ phân tích và đưa ra đề xuất, khi đã confirm tất cả thì mình document lại thành requirement và truyền đạt đến Dev + QC.

**Khoa**: Khi khách hàng đăng user story vậy, Hoàng có thường say no không?

**Hoàng**: Có chứ. Ví dụ mình làm một cái popup, có rất nhiều cách để tắt popup. Thì mình có thể để xuất cho khách vì sao nên dùng dấu chéo (x) để tắt. Popup to quá thì mình giải thích có thể gây khó chịu cho user, mình nên làm sao để thân thiện với user hơn.

Ví dụ khách có nghĩ ra một tính năng nhưng khi trao đổi với team dev mà tính năng đó quá phức tạp thì mình có thể deal lại với khách để cân nhắc độ ưu tiên và mức độ xây dựng của tính năng này.

**Khoa**: Tức là mình có thể thảo luận với team dev, desinger về tính năng, nhưng BA vẫn là người quyết định cuối cùng và chốt với khách hàng.

**Hoàng**: Đúng rồi. Đa số các tính năng mình sẽ được tự chốt với khách hàng.

**Khoa**: Khi dev làm xong thì BA là người làm UAT?

Hoàng: Đúng rồi, nhưng trước đó là có team QC kiểm tra thật kỹ luôn. Và mình cũng trao đổi phần kiểm thử với QC.

**Khoa**: Vậy là khi khách hàng pass cái UAT thì có 2 trường hợp: có thể khách hài lòng hoặc không. Vậy có trường hợp nào sau UAT mà khách muốn chỉnh sửa không?

**Hoàng**: Có chứ. Vì mình còn non kinh nghiệm nên thỉnh thoảng cũng có một số trường hợp. Cũng cái ví dụ popup, mình có trao đổi với anh frond-end là làm sao cho show popup nó mượt đúng ý khách hàng. Nhưng bên khách cũng chưa hình dung được. Nên mình cứ discuss là cứ làm đi, khách họ sẽ có feedback sau.

**Khoa**: À, tức là nếu có chỉnh sửa cũng những thứ lặt vặt thôi, vì hầu như đã trao đổi với khách lúc đầu rồi.

**Hoàng**: Um, vì dự án lần này khách khá quan trọng về UI/UX nhưng mà design họ gửi chỉ có mobile & desktop thôi. Có thể ipad nó chưa tốt nên BA có thể linh động để trao đổi phần này với khách hàng. Có thể làm trước luôn rồi đưa khách hàng nhận xét vì mình biết là những cái này sửa tốn rất ít thời gian so với tổng thời gian xây dựng tính năng.

**Khoa**: À, thà là deal trước với khách hàng những cái core feature chính, còn mấy cái lặt vặt cứ làm rồi show lên cho khách nhận xét

**Hoàng**: Um, đúng rồi.

**Khoa**: Ngoài team phát triển sản phẩm, BA có giao tiếp với những team khác như sale, marketing gì không?

**Hoàng**: Những công ty và team khác mình không biết. Nhưng hiện tại dự án này team mình không có giao tiếp với team sale, marketing nữa. Có thể mấy anh Sếp ở trên lo rồi. hehee

**Khoa**: Vậy sắp tới Hoàng có dự định học gì để cải thiện kỹ năng BA của mình không.

**Hoàng**: Thứ nhất là tiếng Anh giao tiếp để tự tin với khách hàng nước ngoài rồi. Ngoài ra mình dự định học một khoá về BA để biết rõ chuẩn quy trình BA là như thế nào.

**Khoa**: Hoàng có lời khuyên gì cho những bạn muốn làm BA không? Có nên theo con đường của Hoàng là làm QC rồi chuyển qua BA, hay intern thẳng BA luôn?

**Hoàng**: Mình phân làm 2 đối tượng. Đối tượng thứ nhất là chưa tìm hiểu gì về BA thì nên apply QC để hiểu về quy trình, cách làm việc trong team, một số kỹ năng về document sau đó mình làm BA tốt hơn.

Còn những bạn có khả năng tự học, kỹ năng mềm tốt, giao tiếp tốt thì nên appy luôn vị trí intern BA tốt hơn.

**Khoa**: Một số bạn sẽ nói là những kỹ năng mềm khi tham gia những câu lạc bộ, Công tác Xã hội hay Đoàn-Hội gì đó thì tốn thời gian không có ích gì thì Hoàng có lời khuyên gì cho những bạn đó không?

**Hoàng**: Thực ra thì không nhất thiết phải tham gia. Các bạn còn nhiều cách khác như là đi làm thêm như làm trợ giảng ở các trung tâm tiếng Anh. Tham gia những công việc như là dẫn khách du lịch, đi tour. Vừa biết cách nói chuyện với khách hàng vừa tăng khả năng tiếng Anh của bản thân.

Công việc đơn giản hơn là các bạn có thể làm ở những quán cà phê với vị trí bộ phận tiếp tân, phục vụ để hiểu cách làm hài lòng khách hàng, cách nói chuyện với khách hàng.

Bởi vì khi làm BA sẽ có nhiều trường hợp mình rất là khó chịu với khách hàng thì mình phải học cách kiềm chế bản thân.

Nhưng mà tham gia rõ câu lạc bộ trường học là một trải nghiệm rất là tốt. Mình thấy là nó cho mình rất nhiều thứ luôn á. Ví dụ như mình là Đội trưởng Đội Công tác Xã hội nên mình sẽ có những cơ hội đến gặp trực tiếp địa phương, làm việc với chính quyền địa phương để trao đổi về lịch trình của các chương trình tình nguyện.

Mình cũng là người quyết định lịch trình của các hoạt động này và mình biết cách làm các quy trình riêng cho từng địa phương tại vì mỗi địa phương sẽ có cái cách làm việc khác nhau

**Khoa**: Tức là nó cũng na ná giống như BA về cái quy trình giống như là mình làm việc với khách hàng là là nói chuyện với chính quyền địa phương còn làm việc với team phát triển sản phẩm là quay về trường xin giấy tờ.

**Hoàng**: Đúng rồi đó.

**Khoa**: Cảm ơn Hoàng về buổi nói chuyện, với những bạn muốn trao đổi thêm với Hoàng thì có thể liên hệ qua kênh nào nhỉ?
FB: https://www.facebook.com/hoangpm96
Mail: hoangpm.qn96@gmail.com

![Hoang Phan Avatar]({{site.baseurl}}/images/img/qc-to-ba/hoang-phan-avatar.jpg)
*Đây là Hoàng nhé!*

## 3. Kết

Qua buổi phỏng vấn trên, mình nghĩ bạn cũng có cái nhìn tổng quan về công việc của QC và BA rồi. Một số kỹ năng không thể thiếu của BA: Giao tiếp, phân tích, xử lý vấn đề, quản lý.

Ngoài ra khi chuyển sang một vị trí mới mà chưa có kinh nghiệm gì ở vị trí mới đó thì thử intern cũng là lựa chọn không tồi.

Thứ ba là nhiều khi nghề chọn người cũng đúng bạn à. Lúc trước thấy mình [code dạo iOS](https://niviki.com/tinh-co-code-dao-tren-upwork/){:target="_blank"}, Hoàng cũng apply thử vị trí iOS nhưng… rớt rồi chuyển sang làm QC, sau đó mới sang BA. Nếu không có lần rớt đó, chắc giờ Hoàng nó cũng làm iOS dev rồi chăng?

Cho nên [phỏng vấn rớt](https://niviki.com/kinh-nghiem-phong-van-product-manager-product-owner/){:target="_blank"} cũng không phải là gì to tát nhé bạn. [#beyourself](https://niviki.com/what-i-learned-in-2018/){:target="_blank"}
