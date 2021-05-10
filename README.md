# Game_Ninja
Tên game: Ninja Đại Chiến

Link Video demo:https://drive.google.com/file/d/1rBJOAEuYcg12846is38jBVJL4qdMABwW/view?usp=sharing

*Những thư viện được sử dụng
-SDL2-2.0.14
-SDL2_image-2.0.5
-SDL2_mixer-2.0.4
-SDL2_ttf-2.0.15

*Hướng dẫn cài:
- Tải file zip từ github về và giải nén. Link: https://github.com/KhacHieu2704/Game_Ninja
- Cài đặt Codeblock cùng với thư viện SDL2, SDL2_image, SDL2_mixer, SDL2_ttf (Các thư viện đã có sẵn file để cài trong thư mục SDL).
- Sau khi cài đặt hãy mở file đã giải nén, mở file Ninja_Dai_Chien.cbp ( type file: project file) và sau đó hãy trải nghiệm game ^^.

*Cốt truyện: 
Bạn là 1 ninja tài giỏi với nhiệm vụ tiêu diệt quái vật bảo vệ mọi người.

*Hướng dẫn chơi:
- Di chuyển chuột để điều khiển nhân vật.
- Click chuột trái để bắn Rasengan(Đạn).
- Bạn sẽ thua khi HP của bạn về 0 (ban đầu là 100).
- Khi tiêu diệt quái bạn nhận được 1 điểm, tiêu diệt boss bạn nhận được 10 điểm cùng 5HP.
- Cứ tiêu diệt 5 con quái bạn sẽ nhận được 5 điểm.
- Hãy di chuyển khéo léo để không va chạm vào quái vật(-50 HP), boss(-100HP), hay bomb(-10HP).
- Khi bạn bắn đạn phải bomb bạn bị trừ 50HP.
- Để quái vật đi hết màn hình bạn bị trừ 10HP, tương tự với bomb, nhưng với boss thì bạn bị trừ 100HP. 

*Các tính năng vào thuật toán quan trọng
-Ấn Play để chơi. Khi thua, ấn Enter để chơi lại hoặc ESC để thoát.
-Thuật toán va chạm, xử lý va chạm.
-Thuật toán lặp(returngame) để có thể chơi lại game.
-Sử dụng hàm rand() để random quái vật, boss, bomb.

*lưu ý: 
-Max(Điểm cao) lưu theo vòng đời chương trình, exit game = reset Max ^^
-Trò chơi có sử dụng âm thanh vì vậy hãy bật loa để có trải nghiệm tốt nhất.
