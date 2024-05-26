```mermaid
graph TD
  A[Типы гостиниц] --> B[По уровню обслуживания]
  A --> C[По целевой аудитории]
  A --> D[По местоположению]
  A --> E[По длительности пребывания]
  A --> F[По особым характеристикам и специализациям]

  B --> B1[Эконом-класс (Budget)]
  B --> B2[Средний класс (Mid-range)]
  B --> B3[Премиум-класс (Luxury)]

  C --> C1[Бизнес-гостиницы (Business hotels)]
  C --> C2[Туристические гостиницы (Tourist hotels)]
  C --> C3[Спа-отели (Spa hotels)]

  D --> D1[Городские гостиницы (City hotels)]
  D --> D2[Курортные гостиницы (Resort hotels)]
  D --> D3[Аэропортовые гостиницы (Airport hotels)]

  E --> E1[Гостиницы для краткосрочного пребывания (Short-stay hotels)]
  E --> E2[Апарт-отели (Extended-stay hotels)]

  F --> F1[Бутик-отели (Boutique hotels)]
  F --> F2[Исторические гостиницы (Historic hotels)]
  F --> F3[Эко-отели (Eco hotels)]
  F --> F4[Хостелы (Hostels)]
  F --> F5[Тематические гостиницы (Theme hotels)]
