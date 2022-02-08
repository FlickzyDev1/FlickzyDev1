Developer arley = Developer
    .Married()
    .Musician("🎷", Level.Ok)
    .BornIn(Countries.Brazil, year: 1991)
    .LivesIn(Countries.Netherlands, since: 2017)
    .CodesIn(language => language
        .CSharp()
        .TypeScript()
        .JavaScript())
    .Interested(@in => @in
        .SoftwareArchitecture()
        .DomainDrivenDesign()
        .DistributedSystems()
        .ShareIdeas(at: ))
    .Found(at => at
        .Twitter("https://twitter.com/")
        .LinkedIn("https://www.linkedin.com/"));
while (arley.HasLife)
{
    arley.Travel();
    arley.EnjoyLife();
    arley.Code();
}
// todo: find out what is next 😅
