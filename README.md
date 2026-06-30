# letemcook

A weekly meal-planning app with grocery lists and recipes, updated each week.

## Viewing a specific week

Append `?week=M-D-YY` to the URL to jump to any week. Any date within the week works — it snaps to the Sunday automatically:

```
?week=6-7-26   → Week of June 7, 2026
?week=6-10-26  → Week of June 7, 2026 (snaps to Sunday)
?week=4-4-27   → Week of April 4, 2027
```

Dates within the Dec 7 2025 – Dec 27 2026 range load that week's content directly. For dates beyond Dec 27 2026, the app deterministically shuffles the 56 existing recipes using the requested year as a seed, so each future year gets a consistent but distinct ordering. The week label and recipe heading always reflect the date you requested, not the underlying source week.

## Recipes

| Week | Dish |
|------|------|
| Dec 7, 2025 | Tofu Fried Rice |
| Dec 14, 2025 | Sesame Ginger Tofu with Noodles |
| Dec 21, 2025 | Mediterranean Lemon-Herb Tofu Bowls |
| Dec 28, 2025 | Mexican Chipotle Tofu Burrito Bowls |
| Jan 4, 2026 | Korean Gochujang Tofu Rice Bowls |
| Jan 11, 2026 | Japanese Miso Glazed Eggplant & Tofu Rice Bowls |
| Jan 18, 2026 | Thai Peanut Tofu with Rice |
| Jan 25, 2026 | Thai Basil Tofu Stir-Fry (Pad Krapow) |
| Feb 1, 2026 | Chinese Black Pepper Tofu |
| Feb 8, 2026 | Sichuan Dry-Fried Broccoli with Crispy Tofu |
| Feb 15, 2026 | Vietnamese Caramelized Tofu (Đậu Hũ Kho Tiêu) |
| Feb 22, 2026 | Indonesian Nasi Goreng with Crispy Tofu |
| Mar 1, 2026 | Tofu Tikka Masala with Basmati Rice |
| Mar 8, 2026 | Spicy Pork Belly Fried Rice |
| Mar 15, 2026 | Crispy Teriyaki Tofu with Rice |
| Mar 22, 2026 | Twice-Cooked Pork Belly (回锅肉 Hui Guo Rou) |
| Mar 29, 2026 | Spanish Smoky Paprika Tofu with Tomato Rice |
| Apr 5, 2026 | Korean Gochujang Tofu Bowls with Vegetables |
| Apr 12, 2026 | Filipino Adobo Tofu (Adobong Tokwa) with Wok-Wilted Bok Choy |
| Apr 19, 2026 | Kimchi Jjim (Braised Kimchi with Pork Belly & Tofu) |
| Apr 26, 2026 | Century Egg & Shrimp Congee + Ginger Scallion Tofu over Rice |
| May 3, 2026 | Taiwanese Three Cup Tofu (三杯豆腐) |
| May 10, 2026 | Cuban Black Beans & Rice (Moros y Cristianos) with Crispy Tofu |
| May 17, 2026 | Vietnamese Caramelized Lemongrass Tofu (Đậu Hũ Xào Sả Ớt) |
| May 24, 2026 | Multi-Meal Week: Tikka / Japanese Curry / Mapo Tofu & Drunken Noodles |
| May 31, 2026 | Greek Lemon Rice with Chickpeas & Crispy Herbed Tofu |
| Jun 7, 2026 | Jamaican Jerk Tofu with Coconut Rice & Peas |
| Jun 14, 2026 | Indonesian Tahu Kecap (Sweet Soy Glazed Tofu) |
| Jun 21, 2026 | Pad See Ew Fried Rice with Tofu, Egg & Broccoli |
| Jun 28, 2026 | Shawarma-Spiced Tofu with Turmeric Rice & Quick Pickled Onions |
| Jul 5, 2026 | Malaysian Tofu Laksa |
| Jul 12, 2026 | Thai Green Curry Tofu |
| Jul 19, 2026 | Mapo Tofu (麻婆豆腐) |
| Jul 26, 2026 | Kung Pao Tofu (宫保豆腐) |
| Aug 2, 2026 | West African Peanut Stew with Tofu |
| Aug 9, 2026 | Ethiopian Misir Wot with Crispy Tofu |
| Aug 16, 2026 | Turkish Menemen-Style Tofu with Rice |
| Aug 23, 2026 | Peruvian Lomo Saltado–Style Tofu |
| Aug 30, 2026 | Japanese Curry Tofu (カレーライス) |
| Sep 6, 2026 | Korean Japchae (잡채) |
| Sep 13, 2026 | Filipino Sisig-Style Tofu |
| Sep 20, 2026 | Vietnamese Bún Thịt Nướng–Style Tofu Noodles |
| Sep 27, 2026 | Burmese Chickpea Tofu Thoke (Salad) |
| Oct 4, 2026 | Indian Chana Masala with Crispy Tofu |
| Oct 11, 2026 | Sri Lankan Black Curry Tofu |
| Oct 18, 2026 | Mexican Tinga-Style Tofu |
| Oct 25, 2026 | Dan Dan Noodles with Tofu (担担面) |
| Nov 1, 2026 | Korean Tteokbokki-Inspired Tofu (떡볶이) |
| Nov 8, 2026 | Thai Massaman Curry Tofu |
| Nov 15, 2026 | Lebanese Mujaddara with Crispy Tofu |
| Nov 22, 2026 | Chinese Char Siu–Glazed Tofu (叉烧豆腐) |
| Nov 29, 2026 | Jamaican Curry Tofu |
| Dec 6, 2026 | Japanese Yaki Udon with Tofu |
| Dec 13, 2026 | Malaysian Nasi Lemak with Sambal Tofu |
| Dec 20, 2026 | Indian Palak Tofu (Spinach Curry) |
| Dec 27, 2026 | Taiwanese Braised Soy Tofu (滷豆腐) |
