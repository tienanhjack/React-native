# React-native
bộ khởi động  npx create-expo-app@latest
bộ truy cập cd my-app 
mở npm start
 npx đi kèm với npm 5.2+ trở lên, xem hướng dẫn cho các phiên bản npm cũ hơn )

Sau đó mở http://localhost:3000/ để xem ứng dụng của bạn.

Khi bạn đã sẵn sàng triển khai vào sản xuất, hãy tạo một gói thu nhỏ bằng npm run build.

npm bắt đầu

Bắt đầu 
Bạn không cần phải cài đặt hoặc cấu hình các công cụ như webpack hoặc Babel. Chúng được cấu hình sẵn và ẩn để bạn có thể tập trung vào mã.

Tạo một dự án và bạn đã sẵn sàng.

Tạo 
Bạn sẽ cần phải có Node >= 14 trên máy phát triển cục bộ của mình (nhưng không bắt buộc trên máy chủ). Bạn có thể sử dụng nvm (macOS/Linux) hoặc nvm-windows để chuyển đổi phiên bản Node giữa các dự án khác nhau.

Để tạo ứng dụng mới, bạn có thể chọn một trong các phương pháp sau:

npx create-react-app my-app
( npx đi kèm với npm 5.2+ trở lên, xem hướng dẫn cho các phiên bản npm cũ hơn )

npm init react-app my-app
npm init <initializer>có sẵn trong npm 6+

yarn create react-app my-app
yarn createcó sẵn trong Yarn 0.25+

Chọn 
Bây giờ bạn có thể tùy chọn khởi động một ứng dụng mới từ mẫu bằng cách thêm --template [template-name]vào lệnh tạo.

Nếu bạn không chọn mẫu, chúng tôi sẽ tạo dự án của bạn bằng mẫu cơ sở của chúng tôi.

Các mẫu luôn được đặt tên theo định dạng cra-template-[template-name], tuy nhiên bạn chỉ cần cung cấp [template-name]cho lệnh tạo.

npx create-react-app my-app --template [template-name]
Bạn có thể tìm danh sách các mẫu có sẵn bằng cách tìm kiếm "cra-template- * " trên npm.

Tài liệu Mẫu tùy chỉnh của chúng tôi mô tả cách bạn có thể xây dựng mẫu của riêng mình.

Tạo 
Bạn có thể bắt đầu một ứng dụng TypeScript mới bằng cách sử dụng mẫu. Để sử dụng mẫu TypeScript do chúng tôi cung cấp, hãy thêm --template typescriptvào lệnh tạo.

npx create-react-app my-app --template typescript
Nếu bạn đã có một dự án và muốn thêm TypeScript, hãy xem tài liệu Thêm TypeScript của chúng tôi .

Chọn trình 
Khi bạn tạo một ứng dụng mới, CLI sẽ sử dụng npm hoặc Yarn để cài đặt các phụ thuộc, tùy thuộc vào công cụ bạn sử dụng để chạy create-react-app. Ví dụ:

# Run this to use npm
npx create-react-app my-app
# Or run this to use yarn
yarn create react-app my-app
Chạy bất kỳ lệnh nào trong số các lệnh này sẽ tạo một thư mục có tên my-appbên trong thư mục hiện tại. Bên trong thư mục đó, nó sẽ tạo cấu trúc dự án ban đầu và cài đặt các phụ thuộc chuyển tiếp:

my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── serviceWorker.js
    └── setupTests.js
Không cần cấu hình hay cấu trúc thư mục phức tạp, chỉ cần các tệp bạn cần để xây dựng ứng dụng. Sau khi cài đặt xong, bạn có thể mở thư mục dự án của mình:
