 INFORMAX AI-POWERED BODILY INJURY MANAGEMENT PLATFORM
 Proje Çalışma Kılavuzu (500K–1M TL Etap)

 Proje Amacı
Türkiye'nin sigorta sektöründe dijital dönüşümünü hızlandırmak amacıyla geliştirilen Informax, yapay zeka destekli beden hasarı analiz platformudur. Proje, sigorta tazminat süreçlerini kağıtsız, otomatik ve çevreci bir yapıya dönüştürerek:

İşlem sürelerini 7–15 günden 3 dakikaya indirir

Kamu, sigorta şirketleri ve vatandaşlar arasında tam entegre dijital bir köprü kurar

12+ API ile kamu kurumlarıyla gerçek zamanlı veri alışverişi sağlar

Karbon ayak izini minimize eder, yeşil dönüşüme katkı sağlar

 Kullanılan Anahtar Teknolojiler
⚙️ Backend
Node.js / FastAPI / Spring Boot

Microservice Architecture

Kafka Event Streaming

PostgreSQL + Redis + MongoDB

📱 Frontend
React + TypeScript

React Native (Mobil)

Material UI + Custom Design System

🧠 AI/ML
XGBoost + Deep Neural Network + Autoencoder

BERTurk NLP Pipeline

Fraud Detection Ensemble

☁️ DevOps / CI-CD
Kubernetes + Docker + GitLab CI

Terraform + Blue/Green Deployments

Grafana + Prometheus Monitoring


Güvenlik & Uyumluluk
NATO-grade mimari

TLS 1.3, AES-256, OAuth2.0, JWT

KVKK ve GDPR uyumu

ISO 27001, SOC 2 Type II sertifikaları

Modüler Servisler
| Modül                    | Açıklama                                     |
| ------------------------ | -------------------------------------------- |
| `case-manager-service`   | Kaza dosyası oluşturma, süreç yönetimi       |
| `ai-ml-engine-service`   | Tazminat hesaplama ve dolandırıcılık tespiti |
| `notification-service`   | SMS, e-posta, e-Devlet bildirimleri          |
| `api-gateway`            | Yetkilendirme, rate-limit, yönlendirme       |
| `document-service`       | Medikal rapor OCR ve NLP işleme              |
| `fraud-detector-service` | Çoklu modelle anomali analizi                |

 Test Ortamları
 | Ortam                | URL                           | Amaç                           |
| -------------------- | ----------------------------- | ------------------------------ |
| UAT (Pre-Production) | `uat.informax.com.tr`         | Son kullanıcı testleri         |
| API Sandbox          | `sandbox.api.informax.com.tr` | Kurumsal API testi             |
| Demo Portal          | `demo.informax.com.tr`        | Tanıtım ve yatırımcı sunumları |

 Mevcut Başarılar (Haziran 2025)
 SEDDK onayı

 12 Kamu Kurumu API entegrasyonu (E-Nabız, SBM, SGK, UYAP, vs.)

 %99.7 hızlanma (15 gün → 3 dakika)

 45.000+ hasar işleme

 KOSGEB'den 1.065.000 TL destek

 %95+ memnuniyet skoru
 
  API Kullanımı
  POST /api/v1/calculate-compensation

{
  "tc_number": "12345678901",
  "polnet_data": {...},
  "api_data": {
    "E_NABIZ": {...},
    "SGK": {...}
  }
}
Yanıt: total_compensation, confidence_score, fraud_risk_score vb. detayları içerir.

Grup Çalışması – Sorumluluk Paylaşımı
| Ekip Üyesi           | Sorumluluk                                               |
| -------------------- | -------------------------------------------------------- |
| Backend Team         | Mikroservisler, Kafka iş akışı, PostgreSQL veri yapıları |
| AI/ML Team           | Model eğitimi, inference servisi, model versiyonlama     |
| Frontend Team        | Web & mobil UI/UX, e-Devlet entegrasyonu                 |
| DevOps Team          | CI/CD, containerization, monitoring                      |
| Güvenlik & Uyumluluk | OAuth2.0, veri şifreleme, SIEM kuralları                 |

 Belgeler
📄 Milli Teknoloji Raporu

🏗️ Sistem Mimarisi

📊 Demo İstatistikleri ve Performans
 İletişim
İnformax Assist Bilişim Teknolojileri A.Ş.
📧 kadir.mercan@informax.com.tr
📍 Marmara Teknokent, Kocaeli
🌐 www.informax.com.tr

Hazırlayan:
SafeRoom Group / Proje Ortakları
Bu repo, T.C. destekli milli teknoloji atağının bir parçasıdır. Her bir modül; sürdürülebilirlik, güvenlik ve ulusal egemenlik esaslarıyla inşa edilmektedir.
