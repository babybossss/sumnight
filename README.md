# sumnight

Private membership for Thailand's hotels, restaurants and spas.

## MVP demo (`demo/`)

`demo/index.html` is a self-contained interactive prototype (mock data, no backend) for partner presentations:

| Route | What it shows |
|---|---|
| `#home` | Sales page with the membership waiting-list form |
| `#line` | LINE OA chat → LINE Login consent → LIFF registration → approval → member portal (card, perks, voucher wallet, booking request, bookings) |
| `#admin` | Booking console. Switch between **sumnight Concierge** and any **Partner house** to see requests, confirm / offer another time / decline, week board, waiting list approval, members, partners, voucher redemption |

State is kept in the browser's `localStorage`, so two tabs on the same device stay in sync
(guest on `#line`, house on `#admin`). Use **Reset** in the demo bar to restore the sample data.

Photos are hotlinked from Unsplash. The wordmark is a placeholder for the official black/pink logo.

Run locally: open `demo/index.html` in a browser, or `npx serve demo`.
