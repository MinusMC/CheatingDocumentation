# KillAura

#### Tên thường gọi: Aura, Slient Aura, KA, ....

#### Danh mục: Combat
#### Chức năng: Tự động tấn công tất cả thực thể đang ở xung quanh người chơi trong một phạm vi xác định.
#### Phím mặc định: R
#### Video ví dụ: -
#### Settings: 
- MaxCPS: CPS tối đa để tấn công mục tiêu.
- MinCPS: CPS tối thiểu để tấn công mục tiêu.
- HurtTime: Thời giản nghỉ giữa 2 hit, được tính theo tick (20 ticks = 1 giây).
- Range: Khoảng cách có thể tấn công, được tính bằng đơn vị `"mét"` trong Minecraft (1 mét = 1 block).
- ThroughWallsRange: Khoảng cách có thể tấn công xuyên tường, được tính bằng đơn vị `"mét"` trong Minecraft (1 mét = 1 block).
- RangeSprintReducement: Phần phạm vi bị giảm đi do sprint.
- RotationMode: Xoay người chơi đến thực thể. Gồm các mode:
  + Vanilla: Quay người chơi đến thực thể một cách tự nhiên.
  + Spin: Xoay vòng người chơi liên tục nhưng vẫn có thể đánh được thực thể.
  + BackTrack: Quay người chơi đến vị trí cuối cùng của người chơi trước khi người chơi qua một vị trí mới (Có thể tăng bật lùi cho thực thể).
  + None: Không quay người chơi.
- Spin-HitHurtTime: Thời gian nghỉ hit giữa 2 lượt xoay trong Rotation Mode Spin, được tính theo tick (20 ticks = 1 giây).
- MaxSpinSpeed: Tốc độ xoay vòng tối đa của Rotation Mode Spin.
- MinSpinSpeed: Tốc độ xoay vòng tối thiểu của Rotation Mode Spin.
- MaxTurnSpeed: Tốc độ quay tối đa của người chơi đến thực thể.
- MinTurnSpeed: Tốc độ quay tối thiểu của người chơi đến thực thể.
- RoundAngle: Phép làm tròn tốc độ quay.
- RoundAngle-Directions: Độ chính xác của phép làm tròn góc quay.
- NoSendRotation: Quay trong im lặng (Rotation Mode Spin).
- NoHitCheck: Không kiểm tra hit thực thể.
- BlinkCheck: Check có bật Blink module để hủy KillAura.
- Priority: Lựa chọn thực thể ưu tiên:  
  + Health: Khi thực thể thấp máu.
  + Distance: Khi thực thể đứng gần người chơi.
  + Direction: Khi thực thể đang hướng vào mình (?).
  + LivingTime: Khi thực thể có số tick nhiều nhất (?).
  + Armor: Khi thực thể có giáp - (?).
  + HurtTime: Khi thực thể tấn công người chơi có số lượng damage cao hơn so với thực thể đang tấn công người chơi.
- Swing: Animation khi sử dụng KillAura vào thực thể.
- KeepSprint: Vẫn có thể chạy khi đang tấn công thực thể.
- AutoBlock: Tự động chặn kiếm khi đang tấn công mục tiêu. Gồm các mode:
  + None: Không chặn kiếm.
  + Packet: Luôn luôn chặn kiếm.
  + AfterTick: Luôn chặn kiếm cứ sau 1 giây.
- AutoBlockSetting: Setting cho AutoBlock. Gồm các mode:
  + InteractAutoBlock: Blocking ở góc nhìn thứ 3.
  + VerusAutoBlock: Một dạng AutoBlock có thể bypass Verus và cũng có thể đi kèm với các AutoBlock khác.
  + AutoBlockThroughWalls: AutoBlock xuyên tường.
  + SmartAutoBlock: AutoBlock thông minh.
- BlockRate: Tỉ lệ chặn kiếm khi tấn công.
- RayCast: Đánh bất kỳ thực thể nào (Được coi là thực thể) nằm giữa bạn và thực thể (Như thể nhắm và đó và đánh vào). Gồm các mode phụ khi bật:  
  + RayCastIgnored: Giống như RayCast nhưng bỏ qua thực thể và đánh bất cứ thứ gì giữa bạn và thực thể.
  + LivingRayCast: Bỏ qua tất cả các thực thể không phải là thực thể sống.
- AAC: Bypass của AAC AntiCheat
- SilentRotation: Khi KillAura nhắm vào thực thể thì góc nhìn của người chơi sẽ không bị thay đổi.
- Strafe: Tự do di chuyển qua lại thực thể theo hình vòng cung khi bật KillAura. Gồm các mode khi bật:  
  + Silent: Gần như sẽ đi theo hình vòng cung (?).
  + Strict: Di chuyển theo hình vòng cung qua lại thực thể.
  + Off: Không đi theo.
- FOV: Góc nhìn người chơi thấy kẻ địch để KillAura.
- Predict: Phép điều chỉnh HitBox của thực thể. Gồm các mode phụ khi bật:
  + MaxPredictSize: Hệ số HitBox tối đa có thể tấn công được.
  + MinPredictSize: Hệ số HitBox tối thiểu có thể tấn công được.
##### UPDATING...
