<h1>Lütfen Formu Eksiksiz Doldurunuz.</h1>
<hr>
<form>
    <table>
        <tr>
            <td colspan="2" align="center"><h4>Hesap Bilgileriniz</h4></td>
        </tr>
        <tr>
            <td>Kullanıcı Adı :</td>
            <td><input type="text" name="username" placeholder="Kullanıcı adı giriniz" required></td>
        </tr>
        <tr>
            <td>Eposta :</td>
            <td><input type="email" name="eposta" placeholder="Eposta giriniz" required></td>
        </tr>
        <tr>
            <td>Parola :</td>
            <td><input type="password" name="parola" placeholder="parola giriniz" required></td>
        </tr>
        <tr>
            <td colspan="2" align="center"><h4>Kişisel Bilgileriniz</h4></td>
        </tr>
        <tr>
            <td>Ad:</td>
            <td><input type="text" name="ad"></td>
        </tr>
        <tr>
            <td>Soyad :</td>
            <td><input type="text" name="soyad"></td>
        </tr>
        <tr>
            <td>Şehir :</td>
            <td>
                <select name="sehir">
                    <option>Seçiniz</option>
                    <option>Tokat</option>
                </select>
            </td>
        </tr>
        <tr>
            <td>Cinsiyet :</td>
            <td>
                <input type="radio" name="cinsiyet"> Erkek
                <input type="radio" name="cinsiyet"> Kadın
            </td>
        </tr>
        <tr>
            <td>Hobileriniz :</td>
            <td>
                <input type="checkbox" name="hobiler"> Seçiniz
            </td>
        </tr>
    </table>
    <p align="center"><input type="submit" value="Kaydet"></p>
</form>
