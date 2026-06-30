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
| Dec 7, 2025 | [Tofu Fried Rice](https://dnzhng.com/letemcook?week=12-7-25) |
| Dec 14, 2025 | [Sesame Ginger Tofu with Noodles](https://dnzhng.com/letemcook?week=12-14-25) |
| Dec 21, 2025 | [Mediterranean Lemon-Herb Tofu Bowls](https://dnzhng.com/letemcook?week=12-21-25) |
| Dec 28, 2025 | [Mexican Chipotle Tofu Burrito Bowls](https://dnzhng.com/letemcook?week=12-28-25) |
| Jan 4, 2026 | [Korean Gochujang Tofu Rice Bowls](https://dnzhng.com/letemcook?week=1-4-26) |
| Jan 11, 2026 | [Japanese Miso Glazed Eggplant & Tofu Rice Bowls](https://dnzhng.com/letemcook?week=1-11-26) |
| Jan 18, 2026 | [Thai Peanut Tofu with Rice](https://dnzhng.com/letemcook?week=1-18-26) |
| Jan 25, 2026 | [Thai Basil Tofu Stir-Fry (Pad Krapow)](https://dnzhng.com/letemcook?week=1-25-26) |
| Feb 1, 2026 | [Chinese Black Pepper Tofu](https://dnzhng.com/letemcook?week=2-1-26) |
| Feb 8, 2026 | [Sichuan Dry-Fried Broccoli with Crispy Tofu](https://dnzhng.com/letemcook?week=2-8-26) |
| Feb 15, 2026 | [Vietnamese Caramelized Tofu (Đậu Hũ Kho Tiêu)](https://dnzhng.com/letemcook?week=2-15-26) |
| Feb 22, 2026 | [Indonesian Nasi Goreng with Crispy Tofu](https://dnzhng.com/letemcook?week=2-22-26) |
| Mar 1, 2026 | [Tofu Tikka Masala with Basmati Rice](https://dnzhng.com/letemcook?week=3-1-26) |
| Mar 8, 2026 | [Spicy Pork Belly Fried Rice](https://dnzhng.com/letemcook?week=3-8-26) |
| Mar 15, 2026 | [Crispy Teriyaki Tofu with Rice](https://dnzhng.com/letemcook?week=3-15-26) |
| Mar 22, 2026 | [Twice-Cooked Pork Belly (回锅肉 Hui Guo Rou)](https://dnzhng.com/letemcook?week=3-22-26) |
| Mar 29, 2026 | [Spanish Smoky Paprika Tofu with Tomato Rice](https://dnzhng.com/letemcook?week=3-29-26) |
| Apr 5, 2026 | [Korean Gochujang Tofu Bowls with Vegetables](https://dnzhng.com/letemcook?week=4-5-26) |
| Apr 12, 2026 | [Filipino Adobo Tofu (Adobong Tokwa) with Wok-Wilted Bok Choy](https://dnzhng.com/letemcook?week=4-12-26) |
| Apr 19, 2026 | [Kimchi Jjim (Braised Kimchi with Pork Belly & Tofu)](https://dnzhng.com/letemcook?week=4-19-26) |
| Apr 26, 2026 | [Century Egg & Shrimp Congee + Ginger Scallion Tofu over Rice](https://dnzhng.com/letemcook?week=4-26-26) |
| May 3, 2026 | [Taiwanese Three Cup Tofu (三杯豆腐)](https://dnzhng.com/letemcook?week=5-3-26) |
| May 10, 2026 | [Cuban Black Beans & Rice (Moros y Cristianos) with Crispy Tofu](https://dnzhng.com/letemcook?week=5-10-26) |
| May 17, 2026 | [Vietnamese Caramelized Lemongrass Tofu (Đậu Hũ Xào Sả Ớt)](https://dnzhng.com/letemcook?week=5-17-26) |
| May 24, 2026 | [Multi-Meal Week: Tikka / Japanese Curry / Mapo Tofu & Drunken Noodles](https://dnzhng.com/letemcook?week=5-24-26) |
| May 31, 2026 | [Greek Lemon Rice with Chickpeas & Crispy Herbed Tofu](https://dnzhng.com/letemcook?week=5-31-26) |
| Jun 7, 2026 | [Jamaican Jerk Tofu with Coconut Rice & Peas](https://dnzhng.com/letemcook?week=6-7-26) |
| Jun 14, 2026 | [Indonesian Tahu Kecap (Sweet Soy Glazed Tofu)](https://dnzhng.com/letemcook?week=6-14-26) |
| Jun 21, 2026 | [Pad See Ew Fried Rice with Tofu, Egg & Broccoli](https://dnzhng.com/letemcook?week=6-21-26) |
| Jun 28, 2026 | [Shawarma-Spiced Tofu with Turmeric Rice & Quick Pickled Onions](https://dnzhng.com/letemcook?week=6-28-26) |
| Jul 5, 2026 | [Malaysian Tofu Laksa](https://dnzhng.com/letemcook?week=7-5-26) |
| Jul 12, 2026 | [Thai Green Curry Tofu](https://dnzhng.com/letemcook?week=7-12-26) |
| Jul 19, 2026 | [Mapo Tofu (麻婆豆腐)](https://dnzhng.com/letemcook?week=7-19-26) |
| Jul 26, 2026 | [Kung Pao Tofu (宫保豆腐)](https://dnzhng.com/letemcook?week=7-26-26) |
| Aug 2, 2026 | [West African Peanut Stew with Tofu](https://dnzhng.com/letemcook?week=8-2-26) |
| Aug 9, 2026 | [Ethiopian Misir Wot with Crispy Tofu](https://dnzhng.com/letemcook?week=8-9-26) |
| Aug 16, 2026 | [Turkish Menemen-Style Tofu with Rice](https://dnzhng.com/letemcook?week=8-16-26) |
| Aug 23, 2026 | [Peruvian Lomo Saltado–Style Tofu](https://dnzhng.com/letemcook?week=8-23-26) |
| Aug 30, 2026 | [Japanese Curry Tofu (カレーライス)](https://dnzhng.com/letemcook?week=8-30-26) |
| Sep 6, 2026 | [Korean Japchae (잡채)](https://dnzhng.com/letemcook?week=9-6-26) |
| Sep 13, 2026 | [Filipino Sisig-Style Tofu](https://dnzhng.com/letemcook?week=9-13-26) |
| Sep 20, 2026 | [Vietnamese Bún Thịt Nướng–Style Tofu Noodles](https://dnzhng.com/letemcook?week=9-20-26) |
| Sep 27, 2026 | [Burmese Chickpea Tofu Thoke (Salad)](https://dnzhng.com/letemcook?week=9-27-26) |
| Oct 4, 2026 | [Indian Chana Masala with Crispy Tofu](https://dnzhng.com/letemcook?week=10-4-26) |
| Oct 11, 2026 | [Sri Lankan Black Curry Tofu](https://dnzhng.com/letemcook?week=10-11-26) |
| Oct 18, 2026 | [Mexican Tinga-Style Tofu](https://dnzhng.com/letemcook?week=10-18-26) |
| Oct 25, 2026 | [Dan Dan Noodles with Tofu (担担面)](https://dnzhng.com/letemcook?week=10-25-26) |
| Nov 1, 2026 | [Korean Tteokbokki-Inspired Tofu (떡볶이)](https://dnzhng.com/letemcook?week=11-1-26) |
| Nov 8, 2026 | [Thai Massaman Curry Tofu](https://dnzhng.com/letemcook?week=11-8-26) |
| Nov 15, 2026 | [Lebanese Mujaddara with Crispy Tofu](https://dnzhng.com/letemcook?week=11-15-26) |
| Nov 22, 2026 | [Chinese Char Siu–Glazed Tofu (叉烧豆腐)](https://dnzhng.com/letemcook?week=11-22-26) |
| Nov 29, 2026 | [Jamaican Curry Tofu](https://dnzhng.com/letemcook?week=11-29-26) |
| Dec 6, 2026 | [Japanese Yaki Udon with Tofu](https://dnzhng.com/letemcook?week=12-6-26) |
| Dec 13, 2026 | [Malaysian Nasi Lemak with Sambal Tofu](https://dnzhng.com/letemcook?week=12-13-26) |
| Dec 20, 2026 | [Indian Palak Tofu (Spinach Curry)](https://dnzhng.com/letemcook?week=12-20-26) |
| Dec 27, 2026 | [Taiwanese Braised Soy Tofu (滷豆腐)](https://dnzhng.com/letemcook?week=12-27-26) |
