<Type Name="ApplicationHealthStateChunkList" FullName="System.Fabric.Health.ApplicationHealthStateChunkList">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateChunkList : System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.ApplicationHealthStateChunk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateChunkList extends System.Fabric.Health.HealthStateChunkList`1&lt;class System.Fabric.Health.ApplicationHealthStateChunk&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateChunkList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateChunkList&#xA;Inherits HealthStateChunkList(Of ApplicationHealthStateChunk)" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateChunkList = class&#xA;    inherit HealthStateChunkList&lt;ApplicationHealthStateChunk&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthStateChunkList&lt;System.Fabric.Health.ApplicationHealthStateChunk&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Health.ApplicationHealthStateChunk</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Liste mit <see cref="T:System.Fabric.Health.ApplicationHealthStateChunk" /> Elemente.
            </summary>
    <remarks>Die Liste kann über integritätsabfragen Status-Blocks abgerufen werden. Abfragen können als Ergebnis Segmente aufweisen, die eine Nachricht eingefügt werden kann.
            In diesem Fall die Liste der Elemente, die die Nachricht wird zurückgegeben, sowie eine Anzahl, die zeigt, wie viele gesamtelemente sind verfügbar.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateChunkList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Instanziiert eine leere <see cref="T:System.Fabric.Health.ApplicationHealthStateChunkList" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>