<Type Name="StatelessServiceDescription" FullName="System.Fabric.Description.StatelessServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceDescription : System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceDescription extends System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatelessServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceDescription&#xA;Inherits ServiceDescription" />
  <TypeSignature Language="F#" Value="type StatelessServiceDescription = class&#xA;    inherit ServiceDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Erweitert <see cref="T:System.Fabric.Description.ServiceDescription" /> zusätzlichen erforderlichen Informationen zum Erstellen eines zustandslosen Diensts bereitstellen. </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine Instanz der <see cref="T:System.Fabric.Description.StatelessServiceDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceCount">
      <MemberSignature Language="C#" Value="public int InstanceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 InstanceCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceCount As Integer" />
      <MemberSignature Language="F#" Value="member this.InstanceCount : int with get, set" Usage="System.Fabric.Description.StatelessServiceDescription.InstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Anzahl der Instanzen dieser Dienst-Partition. </para>
        </summary>
        <value>
          <para>Die Anzahl der Instanzen dieser Dienst-Partition. </para>
        </value>
        <remarks>
          <para>Die <see cref="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" /> Eigenschaft gibt die Anzahl der Instanzen für diesen Dienst erstellt werden. Die angegebene Anzahl von Instanzen wird von Service Fabric verwaltet werden. Für eine partitionierte statusfreien Dienst <see cref="P:System.Fabric.Description.StatelessServiceDescription.InstanceCount" /> gibt die Anzahl der Instanzen, die pro Partition gespeichert sind.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>