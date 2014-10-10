SAO
===

#SimpleArcObject
  在以往的工作中，我们在使用ArcEngine或者直接调用AO的时候，往往很头疼，明明是很简单的操作，往往在各种各样的接口之间转来转去。这其实不是Esri考虑的不周到，而是他们的AO类库设计的太细致了。细粒度的SDK，使得大多数初学者犯难，本来C#刚刚掌握，又来了一堆面向对象的知识，再加上GIS的一些复杂的原理、版本控制复杂的机制，让AO变成了“阳春白雪”。
  正如标题的意思，本类库的主要目标是对ArcObject的封装，使得.NET开发人员在调用更加贴近.net开发人员的使用习惯。其中一些设计思想参考了其他开源框架、类库的设计，希望能对大家有所帮助。
