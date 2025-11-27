# Adato PM - מערכת ניהול פרויקטים להתחדשות עירונית

מערכת לניהול פרויקטי התחדשות עירונית (פינוי-בינוי, תמ"א 38)

## התקנה מקומית

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## טכנולוגיות

- Django 4.2
- PostgreSQL
- Django REST Framework

## מבנה

- `config/` - הגדרות Django
- `users/` - ניהול משתמשים
- `projects/` - ניהול פרויקטים, בעלי דירות, דירות
- `tasks/` - ניהול משימות ורכבת משימות
