<Type Name="StatefulServiceTypeDescription" FullName="System.Fabric.Description.StatefulServiceTypeDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceTypeDescription : System.Fabric.Description.ServiceTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceTypeDescription extends System.Fabric.Description.ServiceTypeDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceTypeDescription&#xA;Inherits ServiceTypeDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceTypeDescription = class&#xA;    inherit ServiceTypeDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceTypeDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt den Diensttyp der zustandsbehaftete.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceTypeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceTypeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine Instanz der <see cref="T:System.Fabric.Description.StatefulServiceTypeDescription" />-Klasse. </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasPersistedState">
      <MemberSignature Language="C#" Value="public bool HasPersistedState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasPersistedState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceTypeDescription.HasPersistedState" />
      <MemberSignature Language="VB.NET" Value="Public Property HasPersistedState As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPersistedState : bool with get, set" Usage="System.Fabric.Description.StatefulServiceTypeDescription.HasPersistedState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt ein Flag, das angibt, ob dies ein permanenten Dienst ist der Status auf der lokalen Festplatte gespeichert.</para>
        </summary>
        <value>
          <para>Ein Flag, das angibt, ob dies ein permanenten Dienst ist der Status auf der lokalen Festplatte gespeichert.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>