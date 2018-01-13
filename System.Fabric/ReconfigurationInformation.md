<Type Name="ReconfigurationInformation" FullName="System.Fabric.ReconfigurationInformation">
  <TypeSignature Language="C#" Value="public sealed class ReconfigurationInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReconfigurationInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReconfigurationInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReconfigurationInformation" />
  <TypeSignature Language="F#" Value="type ReconfigurationInformation = class" />
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
            Stellt Informationen über die Replikat-Neukonfiguration.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReconfigurationInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReconfigurationInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ReconfigurationInformation" />-Klasse mit Standardwerten.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReconfigurationInformation (System.Fabric.ReplicaRole previousConfigurationRole, System.Fabric.ReconfigurationPhase reconfigurationPhase, System.Fabric.ReconfigurationType reconfigurationType, DateTime reconfigurationStartTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.ReplicaRole previousConfigurationRole, valuetype System.Fabric.ReconfigurationPhase reconfigurationPhase, valuetype System.Fabric.ReconfigurationType reconfigurationType, valuetype System.DateTime reconfigurationStartTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReconfigurationInformation.#ctor(System.Fabric.ReplicaRole,System.Fabric.ReconfigurationPhase,System.Fabric.ReconfigurationType,System.DateTime)" />
      <MemberSignature Language="F#" Value="new System.Fabric.ReconfigurationInformation : System.Fabric.ReplicaRole * System.Fabric.ReconfigurationPhase * System.Fabric.ReconfigurationType * DateTime -&gt; System.Fabric.ReconfigurationInformation" Usage="new System.Fabric.ReconfigurationInformation (previousConfigurationRole, reconfigurationPhase, reconfigurationType, reconfigurationStartTimeUtc)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="previousConfigurationRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="reconfigurationPhase" Type="System.Fabric.ReconfigurationPhase" />
        <Parameter Name="reconfigurationType" Type="System.Fabric.ReconfigurationType" />
        <Parameter Name="reconfigurationStartTimeUtc" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="previousConfigurationRole"></param>
        <param name="reconfigurationPhase"></param>
        <param name="reconfigurationType"></param>
        <param name="reconfigurationStartTimeUtc"></param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ReconfigurationInformation" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousConfigurationRole">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicaRole PreviousConfigurationRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReplicaRole PreviousConfigurationRole" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.PreviousConfigurationRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousConfigurationRole As ReplicaRole" />
      <MemberSignature Language="F#" Value="member this.PreviousConfigurationRole : System.Fabric.ReplicaRole" Usage="System.Fabric.ReconfigurationInformation.PreviousConfigurationRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Die replikatrolle vor der Neukonfiguration. Der Wert <see cref="F:System.Fabric.ReplicaRole.Unknown" />gäbe keine vorherige Neukonfiguration.</para>
          <value>Die vorherigen replikatrolle.</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationPhase">
      <MemberSignature Language="C#" Value="public System.Fabric.ReconfigurationPhase ReconfigurationPhase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReconfigurationPhase ReconfigurationPhase" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.ReconfigurationPhase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationPhase As ReconfigurationPhase" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationPhase : System.Fabric.ReconfigurationPhase" Usage="System.Fabric.ReconfigurationInformation.ReconfigurationPhase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Die aktuelle Phase eine Neukonfiguration. Der Wert <see cref="F:System.Fabric.ReconfigurationPhase.None" /> , wenn keine Neukonfiguration stattfindet.</para>
          <value>Die Phase des aktuellen laufenden Neukonfiguration.</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationStartTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ReconfigurationStartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ReconfigurationStartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.ReconfigurationStartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationStartTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationStartTimeUtc : DateTime" Usage="System.Fabric.ReconfigurationInformation.ReconfigurationStartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <param>Datum Uhrzeit beim Start der Neukonfiguration. Der Wert wird als DateTime in UTC dargestellt. Der Wert wäre <see cref="F:System.DateTime.MinValue" /> , wenn keine Neukonfiguration stattfindet.</param>
          <value>Dem Startzeitpunkt der Neukonfigurierung im UTC-Format.</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationType">
      <MemberSignature Language="C#" Value="public System.Fabric.ReconfigurationType ReconfigurationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReconfigurationType ReconfigurationType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.ReconfigurationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationType As ReconfigurationType" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationType : System.Fabric.ReconfigurationType" Usage="System.Fabric.ReconfigurationInformation.ReconfigurationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <param>Der Typ des eine Neukonfiguration. Der Wert <see cref="F:System.Fabric.ReconfigurationType.None" /> , wenn keine Neukonfiguration stattfindet.</param>
          <value>Der Typ der Neukonfiguration.</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>