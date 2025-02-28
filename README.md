# Stroke-prediction
from django.urls import path
from . import views
urlpatterns=[
    path('',views.index,name='index'),
    path('test_db/', views.test_db_connection),
    path('login',views.login,name='login'),
    path('register',views.register,name='register'),
    path('predict',views.predict,name='predict') 
    path('logout',views.logout,name='logout'),
    path('causes',views.causes,name='causes'),
    path('symptoms',views.symptoms,name='symptoms'),
    path('form',views.form,name='form'),
    path('prediction2',views.prediction2,name='prediction2'),
    path('prediction1',views.prediction1,name='prediction1'),
    path('forgotpwd',views.forgotpwd,name='forgotpwd'),
    path('hospital',views.hospital,name='hospital'),
    path('karimnagar',views.karimnagar,name='karimnagar'),
    path('warangal',views.warangal,name='warangal'),
    path('hyderabad',views.hyderabad,name='hyderabad'),
]
