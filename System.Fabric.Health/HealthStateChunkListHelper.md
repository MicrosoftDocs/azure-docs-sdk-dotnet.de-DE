<Type Name="HealthStateChunkListHelper" FullName="System.Fabric.Health.HealthStateChunkListHelper">
  <TypeSignature Language="C#" Value="public static class HealthStateChunkListHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HealthStateChunkListHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthStateChunkListHelper" />
  <TypeSignature Language="VB.NET" Value="Public Module HealthStateChunkListHelper" />
  <TypeSignature Language="F#" Value="type HealthStateChunkListHelper = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungen für den Integritätsstatus in Blöcken Auflisten von Vorgängen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToArray&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T[] ToArray&lt;T&gt; (this System.Fabric.Health.HealthStateChunkList&lt;T&gt; list);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T[] ToArray&lt;T&gt;(class System.Fabric.Health.HealthStateChunkList`1&lt;!!T&gt; list) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkListHelper.ToArray``1(System.Fabric.Health.HealthStateChunkList{``0})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ToArray(Of T) (list As HealthStateChunkList(Of T)) As T()" />
      <MemberSignature Language="F#" Value="static member ToArray : System.Fabric.Health.HealthStateChunkList&lt;'T&gt; -&gt; 'T[]" Usage="System.Fabric.Health.HealthStateChunkListHelper.ToArray list" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T[]</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="list" Type="System.Fabric.Health.HealthStateChunkList&lt;T&gt;" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ der List-Objekte.</typeparam>
        <param name="list">Die Liste der Integrität Status-Block.</param>
        <summary>
            Ein Array mit den Elementen zurückgegeben in der Liste der Block.
            </summary>
        <returns>Das Array.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>