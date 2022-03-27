# Bordadyn Olga

![My photo](assets/photo.jpg?raw=true)

## Contacts
- [GitHub](https://github.com/olga028383)
- [Telegram](https://t.me/olga_olga028383)
- Discord server rs-school - Olga (@olga028383)

## About me
Attention to detail, responsibility, ability to listen and hear. I love programming and everything connected with it, in fact, what I have been doing for 5 years. I don't smoke and I like to play sports. I came to the project to update and replenish my knowledge in the frontend area.

## Кey skills
HTML5, CSS3, Jquery, bootstrap ,js, react, redux, axios, scss, less, бэм, git, adaptive layout, PHP, mysql, wordpress, bitrix, yii2 and others.


## Code examples

### Javascript
```
const getRandom = (min = 0, max = 1) => {
  const lower = Math.ceil(Math.min(min, max));
  const upper = Math.floor(Math.max(max, max));

  return Math.floor(lower + Math.random() * (upper - lower + 1));
};

const generateNumbers = (min, max) => {
  const randomNumbers = [];

  return () => {
    let id = getRandom(min, max);

    while (randomNumbers.includes(id)) {
      id = getRandom(min, max);
    }

    randomNumbers.push(id);

    return id;
  };
};

```
### php
```
/**
 * Class Favorites
 */
class Favorites
{

    const moduleId = "favorite";

    /**
     * @var array
     */
    private static $instances = array();

    /**
     * The variable contains a data storage object
     * @var mixed
     */
    private $dataStorage;

    /**
     * The function gets the user ID
     * @return bool
     */
    private function getUserId()
    {
        return ($_SESSION['SESS_AUTH']["USER_ID"]) ? $_SESSION['SESS_AUTH']["USER_ID"] : false;
    }

    /**
     * Favorites constructor.
     */
    protected function __construct()
    {
        if($this->getUserId()) {
            $this->dataStorage = DataStorageProperty::getInstance();
        }else{
            $this->dataStorage = DataStorageCookie::getInstance();
        }
    }

    /**
     * @throws \Exception
     */
    public function __wakeup()
    {
        throw new \Exception("Cannot unserialize a singleton.");
    }

    /**
     * @return mixed
     */
    public static function getInstance()
    {

        $cls = static::class;

        if (!isset(static::$instances[$cls])) {
            static::$instances[$cls] = new static;
        }

        return static::$instances[$cls];
    }

    /**
     * The method receives the object in which the data is stored
     * @return DataStorageProperty
     */
    public function getStorageObject()
    {
        return $this->dataStorage;
    }
}
```
## Work experience (from 2007 to present)

- [https://github.com/olga028383/375607-what-to-watch-7](https://github.com/olga028383/375607-what-to-watch-7)
- [https://github.com/olga028383/375607-cinemaddict-14](https://github.com/olga028383/375607-cinemaddict-14)
- [https://github.com/olga028383/375607-kekstagram-22](https://github.com/olga028383/375607-kekstagram-22)
- [https://github.com/olga028383/375607-cat-energy-21](https://github.com/olga028383/375607-cat-energy-21)
- [https://github.com/olga028383/375607-technomart-29](https://github.com/olga028383/375607-technomart-29)
- [https://github.com/olga028383/375607-task-force-1](https://github.com/olga028383/375607-task-force-1)
- [https://github.com/olga028383/375607-keksobooking](https://github.com/olga028383/375607-keksobooking)
- [https://github.com/olga028383/375607-doingsdone](https://github.com/olga028383/375607-doingsdone)

## Education

- Russian State Social University, Moscow
- HTML Academy

## Education 

First level

