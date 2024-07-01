# KillAura

#### Tên thường gọi: Aura, Slient Aura, KA, ....
#### Danh mục: Combat
#### Chức năng: Tự động tấn công tất cả thực thể đang ở xung quanh người chơi trong một phạm vi xác định.
#### Phím mặc định: R
#### Settings: 
- MaxCPS: CPS tối đa để tấn công mục tiêu.
- MinCPS: CPS tối thiểu để tấn công mục tiêu.
- HurtTime: Thời gian còn lại địch sẽ dính sát thương. Khi hurtTime của địch lớn hơn hurtTime client chỉ định thì không đánh.
- Range: Khoảng cách có thể tấn công.
- ThroughWallsRange: Khoảng cách có thể tấn công xuyên tường.
- RotationRange: Khoảng cách có thể xoay về đối thủ.
- Swing: Hiệu ứng kiếm. Có 3 mode:
  + Normal: Chạy hiệu ứng kiếm + gửi packet hiệu ứng.
  + Packet: Chỉ gửi packet hiệu ứng.
  + None: Không gửi hiệu ứng.
- Rotation: Chế độ xoay người chơi đến thực thể.
  + Vanilla: ()
  + NCP: ()
  + Grim: ()
  + Intave: ()
  + None: ()
- Intave-RandomAmount: Lượng tốc độ xoay ngẫu nhiên với Rotation Intave.
- TurnSpeed: Tốc độ quay của người chơi đến mục tiêu.
- KeepRotationLength: Thời gian giữ rotation.
- Priority: Lựa chọn mục tiêu ưu tiên. Client sẽ chọn theo tiêu chí gần nhất như:
  + Health: Thấp máu nhất. ()
  + Distance: Gần khoảng cách mục tiêu nhất. ()
  + HurtResistantTime: Chống chịu yếu nhất. ()
  + Armor: Giáp yếu nhất. ()
  + HurtTime: Sắp bị dính sát thương đầu tiên. ()
- TargetMode: Chế độ đánh.
  + Single: Đánh đơn. ()
  + Switch: Đánh 1 hit 1 người. ()
  + Multi: Đánh nhiều người cùng lúc. ()
- FailSwing: Chạy swing bản legit.
- OnlyHitOnMouseToTarget: Chỉ hit khi chuột xoay vào thực thể.
- AutoBlock: Tự động chặn kiếm khi đang tấn công mục tiêu.
  + None: Không chặn. ()
  + AfterTick: Chặn tại Post Motion và bỏ chặn trước hit. ()
  + Vanilla: Chặn sau hit và bỏ chặn trước hit. ()
  + NewNCP: Bypass AutoBlock dành cho NoCheatPlus. ()
  + RightHold: Chuột phải block. ()
  + Swing: Chặn theo swing. ()
- InteractAutoBlock: AutoBlock dạng giao tiếp với người chơi (Giống như click chuột phải vào NPC).
- AutoBlock-Range: Phạm vi có thể autoblock.
- RayCast: Kiểm tra giữa người chơi và địch có bị chặn bởi người khác không. Nếu có, không đánh.
- SilentRotation: Xoay trong im lặng.
- MovementCorrection: Di chuyển theo góc quay:  
  + Normal: ()
  + LiquidBounce: ()
  + Rise: ()
  + Off: ()
- Predict: Hitbox đoán góc xoay.
- PredictSize: Kích thước hitbox cần đoán góc xoay.
- Circle: Vẽ vòng tròn có thể đánh.
- Accuracy: Số cạnh vẽ hình tròn tương đối.
- Red, Green, Blue, Alpha: Màu của hình tròn (Circle).
