<Type Name="StatelessServiceUpdateDescription" FullName="System.Fabric.Description.StatelessServiceUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceUpdateDescription : System.Fabric.Description.ServiceUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceUpdateDescription extends System.Fabric.Description.ServiceUpdateDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatelessServiceUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceUpdateDescription&#xA;Inherits ServiceUpdateDescription" />
  <TypeSignature Language="F#" Value="type StatelessServiceUpdateDescription = class&#xA;    inherit ServiceUpdateDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceUpdateDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die <see cref="T:System.Fabric.Description.StatelessServiceDescription" /> eines zurzeit ausgeführten Diensts über <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceUpdateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceUpdateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.StatelessServiceUpdateDescription" /> Klasse mit keine Eigenschaften festgelegt.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; InstanceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; InstanceCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatelessServiceUpdateDescription.InstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.InstanceCount : Nullable&lt;int&gt; with get, set" Usage="System.Fabric.Description.StatelessServiceUpdateDescription.InstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den <see cref="P:System.Fabric.Description.StatelessServiceUpdateDescription.InstanceCount" /> von <see cref="T:System.Fabric.Description.StatelessServiceUpdateDescription" /> ab oder legt ihn fest.</para>
        </summary>
        <value>
          <para>Der <see cref="P:System.Fabric.Description.StatelessServiceUpdateDescription.InstanceCount" /> des <see cref="T:System.Fabric.Description.StatelessServiceUpdateDescription" />.</para>
        </value>
        <remarks>
          <para>Siehe <see cref="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" />.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>