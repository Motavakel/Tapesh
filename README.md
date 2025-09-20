
## تپش
این یک برنامه موبایل است که با استفاده از Expo ساخته شده و برای ارائه تجربه‌ای بی‌نقص در زمینه تناسب اندام طراحی شده است. این برنامه به زودی در بازار عرضه خواهد شد و ما هیجان‌زده هستیم که آن را به کاربران سراسر جهان ارائه دهیم!

## ساختار پروژه

پروژه از یک ساختار مدولار و منظم پیروی می‌کند تا مقیاس‌پذیری و نگهداری آن آسان باشد:

```
TAPESH/
├── _layout.tsx
├── app/
│   ├── (tabs)/
│   │   ├── _layout.tsx
│   │   ├── index.tsx
│   │   ├── profile.tsx
│   │   └── reports.tsx
├── onboarding/
│   ├── _layout.tsx
│   │   ├── body-info.tsx
│   │   ├── final-loading.tsx
│   │   ├── gender.tsx
│   │   ├── goal.tsx
│   │   ├── index.tsx
│   │   ├── _layout.tsx
│   │   ├── Exercise.tsx
│   │   ├── index.tsx
│   │   ├── Rest.tsx
│   │   ├── Summary.tsx
│   │   ├── Workout.tsx
│   │   └── WorkoutDetail.tsx
├── assets/
├── node_modules/
├── src/
│   ├── components/
│   │   ├── ExerciseCard.tsx
│   │   ├── GetReadyCountdown.tsx
│   │   ├── SettingsButton.tsx
│   │   ├── SettingsModal.tsx
│   │   ├── Splash.tsx
│   │   └── Timer.tsx
│   ├── hooks/
│   │   ├── useMusicPlayer.ts
│   │   └── useTimer.ts
│   ├── locales/
│   │   ├── en.json
│   │   ├── fa.json
│   │   └── i18n.ts
│   ├── services/
│   │   └── assetMap.ts
│   ├── store/
│   │   ├── index.ts
│   │   ├── musicSlice.ts
│   │   ├── programSlice.ts
│   │   ├── storage.ts
│   │   ├── userSlice.ts
│   │   └── workoutSlice.ts
│   └── types/
│       └── index.ts
```

## فناوری‌ها

- **Expo**: برنامه با Expo ساخته شده و از سیستم مسیریابی قدرتمند آن (Expo Router) برای ناوبری استفاده می‌کند.
- **TypeScript**: در سراسر پروژه برای تایپ استاتیک و قابلیت اطمینان بیشتر کد استفاده شده است.
- **Redux با Redux Persist**: مدیریت وضعیت با Redux انجام می‌شود، با اسلایس‌هایی برای حوزه‌های مختلف. Redux Persist برای حفظ وضعیت در زمان راه‌اندازی مجدد برنامه ادغام شده است.
- **i18n**: پشتیبانی از چندزبانه با فایل‌های محلی (مانند `en.json` و `fa.json`) ارائه می‌شود.
- **هوک‌های سفارشی**: هوک‌هایی مانند `useMusicPlayer` و `useTimer` برای افزایش قابلیت استفاده مجدد و عملکرد طراحی شده‌اند.

## عرضه آینده

منتظر باشید! این پروژه به زودی برای عرضه در بازار آماده می‌شود. ما سخت در حال کار هستیم تا ویژگی‌ها را کامل کرده و تجربه کاربری عالی را تضمین کنیم.

## شروع کار

دستورالعمل‌های راه‌اندازی و اجرای پروژه به زودی نزدیک به تاریخ انتشار اضافه خواهد شد. در حال حاضر، می‌توانید کد را کاوش کنید و مشارکت کنید!
