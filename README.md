# Olá, seja bem vindo <img width="30" src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" alt="Sunglasses emoji" />

## 🙋‍♂️ Sobre mim
``` java
package luanloose

class About : Me() {
    fun getCurrentJob(): Map<String, String> {
        return mapOf(
            "company" to "Mercado Livre",
            "position" to "Software Engineer"
        )
    }

    fun getSkills(): Map<String, List<Class<*>>> {
        return mapOf(
            "php" to listOf(
                Laravel::class.java,
                Lumen::class.java,
                Hyperf::class.java
            ),
            "java" to listOf(
                Spring::class.java,
                Kotlin::class.java
            ),
            "database" to listOf(
                MongoDB::class.java,
                Postgre::class.java,
                MySQL::class.java
            ),
            "dev-ops" to listOf(
                Aws::class.java,
                Kubernetes::class.java
            )
        )
    }

    fun getFutureGoal(): String {
        return "To contribute to open source."
    }
}
``` 
## 😁 Onde me achar:

<a href="https://www.linkedin.com/in/luanloose/">
  <code><img alt="LinkedIn" width="30" src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" /></code>
</a>

<p align="right">
  <a href="https://badges.pufler.dev">
      <img src="https://badges.pufler.dev/visits/luanloose/luanloose" alt="Visitors badge" />
   </a>
</p>

