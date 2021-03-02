#### 0362
[百度](http://www.baidu.com)
```
public interface UserRepository extends JpaRepository<User, Long> {
    User findById(long id);

    void deleteById(Long id);
}
```
