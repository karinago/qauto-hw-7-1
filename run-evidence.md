# Run evidence — tests/add-car.spec.ts

## Команда

```
npx playwright test tests/add-car.spec.ts --project=chromium
```

## Фактичний вивід

```
Running 1 test using 1 worker

  ✓  1 [chromium] › tests/add-car.spec.ts:3:5 › guest adds Audi TT to Garage (2.5s)

  1 passed (3.2s)
```

## Рішення

ACCEPT — тест пройшов без помилок, вивід відповідає очікуванню зі `specs/add-car.md`
(запис `Audi TT` у Garage, URL `/panel/garage`).
