```mermaid
gantt
    title План проекта
    dateFormat  YYYY-MM-DD
    section Этап 1
    Задача A     :a1, 2025-11-15, 7d
    Задача B     :after a1, 5d
    section Этап 2
    Задача C     :2025-11-25, 3d
    Задача D     :crit, after a1, 4d
