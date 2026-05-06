# Design Rules — שקולניק פסיכומטרי Landing Page

## Stack
- Single HTML file (`index.html`)
- Tailwind CSS via CDN (`https://cdn.tailwindcss.com`)
- Lucide icons via CDN (`https://unpkg.com/lucide@latest/dist/umd/lucide.min.js`)
- Google Fonts: Inter
- No build tools

## Layout
- `lang="he" dir="rtl"` on `<html>`
- Full Hebrew RTL layout

## DO
- Light, minimal, clean, modern design
- shadcn-style aesthetic
- Neutral palette: white, gray, stone, with one subtle warm amber accent
- Good typography hierarchy
- Plenty of whitespace
- Mobile responsive
- Use logo from `assets/logo.png`
- Font: Inter from Google Fonts
- Light motion: scroll reveal animations using IntersectionObserver
- Smooth transitions and subtle hover states

## DON'T
- No bright saturated gradients
- No gradient text
- No emoji icons — use Lucide icons only
- No heavy shadows
- No busy patterns
- No dark mode
- No border radius larger than `rounded-2xl`
- No cramped spacing
- No tiny fonts below 14px

## Design Tokens
| Token | Tailwind / Value |
|---|---|
| Background | `bg-white` / `bg-stone-50` |
| Text primary | `text-stone-900` |
| Text secondary | `text-stone-500` |
| Accent | `amber-500` / `amber-600` |
| WhatsApp green | `#25D366` |
| Border | `border-stone-200` |
| Max border radius | `rounded-2xl` |
| Font | Inter (Google Fonts) |

## Asset Paths (URL-encoded)
- Logo: `assets/logo.png`
- Hero video: `mainvideo/%D7%A2%D7%95%D7%AA%D7%A7%20%D7%A9%D7%9C%20308412b66ce5459399bc8768db3347e7.mov`
- Student videos: `studentsvideos/WhatsApp%20Video%202026-05-05%20at%2014.20.2X.mp4` (6 files)
- Testimonials: `testimonials/WhatsApp%20Image%202026-05-05%20at%2014.26.2X...jpeg` (7 files)
- Grades: `grades/WhatsApp%20Image%202026-05-05%20at%2014.28.3X...jpeg` (7 files)

## External Links (all open in new tab)
- WhatsApp CTA: `https://wa.me/972547461665`
- Instagram: `https://www.instagram.com/shkolnikpsychometry`
- TikTok: `https://www.tiktok.com/@shkolnik.psychometry`
- Facebook: `https://www.facebook.com/share/1A7cACDTaK/`
