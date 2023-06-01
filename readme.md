# EncrypterApp
Всем хай, тут я опишу вашу задачу.
 Существует абстрактный класс:
```csharp
public abstract class BaseEncryptionAlgorithm() {
    public abstract string Encrypt(string text);
    public abstract string Decrypt(string text);
}
```
Ваша задача заключается в том, чтобы скачать этот класс, создать свой и унаследовать его от базового.

Далее необходимо реализовать в своём классе два метода: шифровку и расшифровку. Так же класс должен иметь ключ в конструкторе. Примерный вид вашего класса:
```csharp
public class CezarEncrypt(int key) : BaseEncryptionAlgorithm
{
        public string Encrypt(string input) 
        {
            /*
                Ваша реализация шифрования
            */
            return result;
        }
        public string Decrypt(string input) 
        {
            /*
                Ваша реализация шифрования
            */
            return result;
        }
}
```
Далее необходимо скинуть ваш класс Никите или Паше.
Всем спасибо и удачи!
![kity](kity.jpg)

