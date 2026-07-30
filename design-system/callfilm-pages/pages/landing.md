# CallFilm landing page override

This page intentionally follows the live
[`akra.kr/quick-translate`](https://akra.kr/quick-translate/) product-page
convention. These rules override `../MASTER.md`.

## Visual language

- Background: `#09090b` (Zinc 950)
- Raised surface: white at 3–6% opacity
- Border: white at 10–16% opacity
- Primary text: `#ffffff`
- Body text: `#d4d4d8`
- Muted text: `#a1a1aa`
- Accent: `#93c5fd` / `#dbeafe`
- Heading: Playfair Display + Noto Serif KR
- Body: Pretendard
- Card radius: 16–17px
- Button radius: 9px; pill navigation and status chips are the only full pills

## Layout

1. Fixed rounded Akra navigation
2. Two-column product hero led by AI captions and real caption screens
3. Four-column AI caption proof strip
4. Dedicated two-screen AI caption proof section
5. Six feature cards in a 3×2 grid
6. Three real-screen cards
7. Two-column usage and cautions
8. Light Android market status CTA

Use 1280px maximum content width and 112px desktop section spacing. Collapse to
one column without horizontal scrolling at 820px and below.

## AI caption treatment

- AI captions are the primary product promise, not a secondary feature card.
- Pair the real on-device model selector with the real caption preview screen.
- Keep `기기 내 AI`, `자막 외부 전송 없음`, `외부 업로드 없음`, and the Pixel 4
  verification evidence adjacent to the screenshots.
- Describe the concrete flow as speech recognition, timestamp alignment, and MP4
  burn-in. Do not use vague AI claims or imply that unavailable cloud providers
  can be selected.

## Product-state rules

- Show the real version as `v1.0.0` and the Android version code as `BUILD 1`.
- Say `Android 마켓 다운로드 예정` until an official store URL exists.
- Do not imitate a Google Play badge or expose a direct APK download.
- Do not invent ratings, user counts, reviews, or a release date.

## Accessibility and motion

- Minimum control height: 44px; primary actions use 56px.
- Keep visible `:focus-visible` outlines.
- Normal text contrast must meet 4.5:1.
- Honor `prefers-reduced-motion`.
- Validate at 375px, 768px, 1024px, and 1440px with no horizontal overflow.
