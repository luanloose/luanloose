# Olá, seja bem vindo <img width="30" src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" alt="Sunglasses emoji" />

## 🙋‍♂️ Sobre mim
``` php
<?php

namespace luanloose;

class About extends Me
{
    public function getCurrentJob(): array
    {
        return [
          'company' => 'Ifood',
          'position' => 'Software Engineer'
        ];
    }

    public function getSkills(): array
    {
        return [
          'php' => [
            Laravel::class,
            Lumen::class,
            Hyperf::class,
          ],
          'java' => [ 
            Spring::class, 
            Kotlin::class,
          ],
          'database' => [
            MongoDB::class,
            Postgre::class,
            MySQL::class,
          ],
          'dev-ops' => [
            Aws::class,
            Kubernetes::class
          ],
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
``` 
## 😁 Onde me achar:

<a href="https://www.linkedin.com/in/luanloose/">
  <code><img alt="LinkedIn" width="30" src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" /></code>
</a>

<a href="https://www.instagram.com/luanloose/?hl=pt-br">
  <code><img alt="Instagram" width="30" src="https://cdn.worldvectorlogo.com/logos/instagram-2-1.svg" /></code>
</a>

<p align="right">
  <a href="https://badges.pufler.dev">
      <img src="https://badges.pufler.dev/visits/luanloose/luanloose" alt="Visitors badge" />
   </a>
</p>

