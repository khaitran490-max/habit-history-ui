# Ghi chú design system (K2 — Khải)

Màu và kích thước lấy từ `colors.xml`, `dimens.xml`. Khi Figma chốt giá trị khác thì chỉ sửa 2 file này, không sửa trong layout.

## Màu

| Tên | Dùng cho |
|-----|----------|
| `primary` | Nút chính, viền "hôm nay", điểm nhấn |
| `on_primary` | Chữ/icon trên nền `primary` và trên ô "đã hoàn thành" |
| `background` | Nền toàn màn hình |
| `surface` | Card, ô nhập, nền ô ngày bỏ lỡ |
| `text_primary` | Tiêu đề, nội dung chính |
| `text_secondary` | Chú thích, tên thứ, ngày chưa tới |
| `done` | Trạng thái đã hoàn thành (ô lịch, dấu tích) |
| `missed` | Trạng thái bỏ lỡ (viền ô lịch) |

## Kích thước

| Tên | Dùng cho |
|-----|----------|
| `space_xs` 4dp | Khe nhỏ giữa các phần tử sát nhau |
| `space_s` 8dp | Khoảng cách trong cùng một nhóm |
| `space_m` 16dp | Padding màn hình, khoảng cách giữa các khối |
| `space_l` 24dp | Khoảng cách giữa các phần lớn |
| `radius_card` 12dp | Bo góc card |
| `text_title` 22sp | Tiêu đề màn hình |
| `text_body` 16sp | Nội dung |
| `text_caption` 13sp | Chú thích |

## Drawable

- `bg_day_done`, `bg_day_missed`, `bg_day_today`: nền ô ngày trong lịch.
- `bg_legend_dot_*`: chấm màu ở phần chú thích.
- `ic_chevron_left`, `ic_chevron_right`: nút chuyển tháng.

## Style trong themes.xml

`HistoryWeekday` (tên thứ), `HistoryLegend` (chú thích màu). Theme app là `Theme.HabitTracker`, nền tối.
