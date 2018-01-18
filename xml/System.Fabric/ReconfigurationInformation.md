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
            <span data-ttu-id="ff3ea-101">Stellt Informationen über die Replikat-Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-101">Represents information about the replica reconfiguration.</span></span>
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
          <para><span data-ttu-id="ff3ea-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ReconfigurationInformation" />-Klasse mit Standardwerten.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-102">Initializes a new instance of the <see cref="T:System.Fabric.ReconfigurationInformation" /> class with default values.</span></span></para>
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
          <para><span data-ttu-id="ff3ea-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ReconfigurationInformation" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-103">Initializes a new instance of the <see cref="T:System.Fabric.ReconfigurationInformation" /> class.</span></span></para>
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
          <para><span data-ttu-id="ff3ea-104">Die replikatrolle vor der Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-104">The replica role prior to the reconfiguration.</span></span> <span data-ttu-id="ff3ea-105">Der Wert <see cref="F:System.Fabric.ReplicaRole.Unknown" />gäbe keine vorherige Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-105">The value would be <see cref="F:System.Fabric.ReplicaRole.Unknown" />if there was no previous reconfiguration.</span></span></para>
          <value><span data-ttu-id="ff3ea-106">Die vorherigen replikatrolle.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-106">The previous replica role.</span></span></value>
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
          <para><span data-ttu-id="ff3ea-107">Die aktuelle Phase eine Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-107">The current phase of the reconfiguration.</span></span> <span data-ttu-id="ff3ea-108">Der Wert <see cref="F:System.Fabric.ReconfigurationPhase.None" /> , wenn keine Neukonfiguration stattfindet.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-108">The value would be <see cref="F:System.Fabric.ReconfigurationPhase.None" /> if no reconfiguration is taking place.</span></span></para>
          <value><span data-ttu-id="ff3ea-109">Die Phase des aktuellen laufenden Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-109">The phase of current ongoing reconfiguration.</span></span></value>
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
          <param><span data-ttu-id="ff3ea-110">Datum Uhrzeit beim Start der Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-110">The date time when reconfiguration started.</span></span> <span data-ttu-id="ff3ea-111">Der Wert wird als DateTime in UTC dargestellt.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-111">The value is represented as DateTime in UTC.</span></span> <span data-ttu-id="ff3ea-112">Der Wert wäre <see cref="F:System.DateTime.MinValue" /> , wenn keine Neukonfiguration stattfindet.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-112">The vlaue would be <see cref="F:System.DateTime.MinValue" /> if no reconfiguration is taking place.</span></span></param>
          <value><span data-ttu-id="ff3ea-113">Dem Startzeitpunkt der Neukonfigurierung im UTC-Format.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-113">The start date time of reconfiguration in UTC format.</span></span></value>
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
          <param><span data-ttu-id="ff3ea-114">Der Typ des eine Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-114">The type of the reconfiguration.</span></span> <span data-ttu-id="ff3ea-115">Der Wert <see cref="F:System.Fabric.ReconfigurationType.None" /> , wenn keine Neukonfiguration stattfindet.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-115">The value would be <see cref="F:System.Fabric.ReconfigurationType.None" /> if no reconfiguration is taking place.</span></span></param>
          <value><span data-ttu-id="ff3ea-116">Der Typ der Neukonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ff3ea-116">The type of reconfiguration.</span></span></value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>