Z-Anahtar'da Nasıl Hesap Oluşturulur ve Giriş Yapılır
=====

.. _installation:

Installation
------------

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Mikail
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

Z-Anahtar’da Nasıl Hesap Oluşturulur ve Giriş Yapılır
----------------
1.	Z-Anahtar’da Nasıl Hesap Oluşturulur
----------------
Z-Anahtar’da bir hesaba sahip olabilmek için 2 farklı hesap açma yöntemi vardır.

a.	Hızlı Giriş: Telefon numarası ve mail adresi ile kayıt olarak yapılan bir giriş yöntemidir. 
Aşağıdaki alanlarda arzu edilen bilgiler kayıt edilerek bir hesap açılabilmektedir.

 .. image:: C:\Users\TCEMBALCI\Desktop/Header+Blog.png
   :width: 1500
   

b.	e-Devlet İle Kayıt: TCKN bilgisi ve e-Devlet şifresi ile Z-Anahtar’a kayıt açılabilmektedir. Bu kayıt sayesinde direkt olarak uygulamaya girilebilmektedir.
 





2.	Z-Anahtar’a Nasıl Giriş Yapılır?
----------------
Z-Anahtar’a giriş yapabilmenin 3 farklı yöntemi vardır.

a.	Hızlı Giriş: Hızlı giriş ile sadece cep telefonu numarası girerek giriş yapılabilmektedir. Öncelikle Z-Anahtar’a tanımlanan cep telefonu numarası girilir ve akabinde cep telefona gelen OTP mesajı ile işlem doğrulanır. Akabinde de kullanıcı daha önceden belirlediği hızlı giriş şifresi ile Z-Anahtar’a giriş yapar.

b.	
   

c.	e-Devlet İle Giriş: e-Devlet ile girişte kullanıcı e-Devlet girişine yönlendirilir. Akabinde TCKN ve e-Devlet şifresi girilerek kullanıcı giriş yapmaktadır.

 

d.	Biyometrik Giriş: Biyometrik girişte kullanıcı Z-Anahtar uygulamasına Face ID’sini kayıt eder ve bu Face ID ile direkt olarak uygulamaya girebilmektedir.


