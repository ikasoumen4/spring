# DI(Dependency Injection)
依存性の注入。
クラス間の依存関係を設定するコードをクラスの中から可能な限り排除し、テストを行いやすいようにする。

# a

# DIのデザインパターン
[参考](http://qiita.com/ritukiii/items/de30b2d944109521298f)
DIを実現する手法として、以下のパターンが存在する。（言語はJavaとは限らない)

- DIコンテナパターン
- サービスロケータパターン



# @SpringBootApplication
@Configuration と @EnableAutoConfiguration と @ComponentScan を設定したのと同じ意味になる。

# @ComponentScan
@Componentがスキャンの対象となる。

# @Component
Spring DIにおける基本アノテーション。

@EnableAutoConfiguration
@ComponentScan
@Configuration
@Component
@Bean
@Controller
@RequestMapping
@RequestParam
@Autowired
@Entity
@Id
@GeneratedValue import javax.persistence.GeneratedValue