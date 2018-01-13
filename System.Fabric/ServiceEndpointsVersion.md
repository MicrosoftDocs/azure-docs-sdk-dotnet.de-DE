<Type Name="ServiceEndpointsVersion" FullName="System.Fabric.ServiceEndpointsVersion">
  <TypeSignature Language="C#" Value="public sealed class ServiceEndpointsVersion" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceEndpointsVersion extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceEndpointsVersion" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceEndpointsVersion" />
  <TypeSignature Language="F#" Value="type ServiceEndpointsVersion = class" />
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
      <para>Zum Vergleich von zwei <see cref="T:System.Fabric.ServiceNotification" /> -Objekte und zu bestimmen, welche Benachrichtigungsereignis anderen vorausgeht.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Compare">
      <MemberSignature Language="C#" Value="public int Compare (System.Fabric.ServiceEndpointsVersion other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 Compare(class System.Fabric.ServiceEndpointsVersion other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceEndpointsVersion.Compare(System.Fabric.ServiceEndpointsVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Compare (other As ServiceEndpointsVersion) As Integer" />
      <MemberSignature Language="F#" Value="member this.Compare : System.Fabric.ServiceEndpointsVersion -&gt; int" Usage="serviceEndpointsVersion.Compare other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.ServiceEndpointsVersion" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>Die andere Version als Vergleichswert.</para>
        </param>
        <summary>
          <para>Vergleicht diese Version mit der Version der <paramref name="other" />.</para>
        </summary>
        <returns>
          <para>NULL, wenn diese und <paramref name="other" /> sind gleichwertig, ein negativer Wert, wenn dies ist kleiner als <paramref name="other" />, und ein positiver Wert ist dies größer als <paramref name="other" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>