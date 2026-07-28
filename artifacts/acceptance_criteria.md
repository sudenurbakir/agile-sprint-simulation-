# Acceptance Criteria

## Amaç

Bu doküman, Sprint 01 kapsamında geliştirilecek User Story'lerin kabul kriterlerini tanımlamak amacıyla hazırlanmıştır.

---

# Acceptance Criteria

## US-01 - Kullanıcı Girişi

### Kabul Kriterleri

**Given** kullanıcı geçerli bir kullanıcı hesabına sahiptir.

**When** kullanıcı geçerli kullanıcı bilgileriyle giriş yapar.

**Then** sistem kullanıcıyı başarıyla oturum açmış duruma getirmelidir.

---

**Given** kullanıcı geçersiz kullanıcı bilgileri girer.

**When** giriş işlemini gerçekleştirir.

**Then** sistem uygun bir hata mesajı göstermeli ve oturum açılmamalıdır.

---

## US-02 - Görev Oluşturma

### Kabul Kriterleri

**Given** kullanıcı oturum açmıştır.

**When** kullanıcı gerekli görev bilgilerini girerek kaydetme işlemini gerçekleştirir.

**Then** sistem yeni görevi oluşturmalı ve görev listesine eklemelidir.

---

**Given** kullanıcı zorunlu alanları doldurmamıştır.

**When** görev oluşturmayı dener.

**Then** sistem görev oluşturulmamalı ve eksik alanlar hakkında kullanıcıyı bilgilendirmelidir.

---

## US-03 - Görev Listesini Görüntüleme

### Kabul Kriterleri

**Given** kullanıcının daha önce oluşturulmuş görevleri bulunmaktadır.

**When** kullanıcı görev listesini açar.

**Then** sistem kullanıcıya tüm görevlerini liste halinde göstermelidir.

---

**Given** kullanıcının henüz oluşturulmuş görevi bulunmamaktadır.

**When** kullanıcı görev listesini görüntüler.

**Then** sistem boş liste bilgisini veya uygun bir bilgilendirme mesajını göstermelidir.

---

# Notlar

* Acceptance Criteria, User Story'lerin başarıyla tamamlandığının doğrulanması amacıyla hazırlanmıştır.
* Sprint Review sırasında User Story'lerin kabulü bu kriterlere göre değerlendirilir.
* Kabul kriterleri gerektiğinde Product Owner ve Scrum Takımı tarafından güncellenebilir.
