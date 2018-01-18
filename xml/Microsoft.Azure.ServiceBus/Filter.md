<Type Name="Filter" FullName="Microsoft.Azure.ServiceBus.Filter">
  <TypeSignature Language="C#" Value="public abstract class Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Filter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Filter" />
  <TypeSignature Language="F#" Value="type Filter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="87963-101">Beschreibt einen Filterausdruck, der für eine Nachricht ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="87963-101">Describes a filter expression that is evaluated against a Message.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="87963-102">Filter ist eine abstrakte Klasse mit dem folgenden konkrete Implementierungen: <list type="bullet"> <item> <b>SqlFilter</b> , ein Filters mithilfe von SQL-Syntax darstellt. </item><item><b>CorrelationFilter</b> , der eine Optimierung für die Korrelation Gleichheitsausdrücke bereitstellt.</item></list></span><span class="sxs-lookup"><span data-stu-id="87963-102">Filter is an abstract class with the following concrete implementations: <list type="bullet"><item><b>SqlFilter</b> that represents a filter using SQL syntax. </item><item><b>CorrelationFilter</b> that provides an optimization for correlation equality expressions.</item></list></span></span></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.FalseFilter" />
  </Docs>
  <Members />
</Type>