### Привет /)
```async function legend() {
  const lancerCruz = require('150iq.js');
  const chalk = require('chalk');

  let doing = ['Sleeping', 'Eating', 'Coding'];
  let langs = ['JavaScript', 'NodeJS'];
  let tools = ['Windows', 'Discord', 'GitHub'];

  let practice = await LancerCruz.randomize(doing, langs, tools);

  let lifeStoryPart1 = `Учусь в школе, занимаюсь кодингом, 16 лет`;
  let lifeStoryPart2 = `Больше всего времени я провожу в играх с друзьями`;
  let lifeStoryPart3 = `Discord отличный мэссэнджер, поэтому я выбрал именно его. Мой первый аккаунт был создан в 2016г`;

  console.log(chalk.blue(lifeStoryPart1, lifeStoryPart2, lifeStoryPart3));
}
exports.lancercruz = legend;
