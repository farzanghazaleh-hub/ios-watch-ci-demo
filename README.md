# WatchDemo – iOS + Apple Watch CI demosu

Gömülü Apple Watch uygulaması içeren bir iOS projesinin CI üzerinde arşivlenmesini gösteren, müşteri kodu içermeyen örnek proje.

- `project.yml`: XcodeGen proje tanımı (Xcode projesi CI'da üretilir)
- `fastlane/Fastfile`: imzasız archive lane'i
- `.github/workflows/1-kesif.yml`: runner'daki Xcode ve SDK envanteri
- `.github/workflows/2-demo.yml`: A) mevcut durum, B) watchOS ön kontrolü ve kurulumu ile önerilen çözüm
