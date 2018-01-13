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
            Beschreibt einen Filterausdruck, der für eine Nachricht ausgewertet wird.
            </summary>
    <remarks>
            Filter ist eine abstrakte Klasse mit dem folgenden konkrete Implementierungen: <list type="bullet"> <item> <b>SqlFilter</b> , ein Filters mithilfe von SQL-Syntax darstellt. </item><item><b>CorrelationFilter</b> , der eine Optimierung für die Korrelation Gleichheitsausdrücke bereitstellt.</item></list></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.FalseFilter" />
  </Docs>
  <Members />
</Type>