# Bogdan Vdovenko

## Contact

 * +380679350540
 * raden2453@gmail.com
 * Discord: @baronraven

## About Me

 Serlf-tought wannabe programmer who wants to learn programming languages to independently create his own projects

## Skills

 * C#
 * C++

## Code Example

```
public class Gun : MonoBehaviour
{
    public GameObject bullet;
    public Transform bulletSpawn;
    public float fireRate = 1f;

    void Start()
    {
        StartCoroutine(Shoot());
    }

    IEnumerator Shoot()
    {
        Instantiate(bullet, bulletSpawn.position, bulletSpawn.rotation);
        yield return new WaitForSeconds(fireRate);
        StartCoroutine(Shoot());
    }
}
```

## Experience

 * [Global Game Jam 2024](https://globalgamejam.org/games/2024/laugh-em-8)

## Education

 * Odesa Lyceum №38

## Languages

 * Russain
 * Ukrainian
 * Englis
 * French
