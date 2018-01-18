<Type Name="HealthReport" FullName="System.Fabric.Health.HealthReport">
  <TypeSignature Language="C#" Value="public abstract class HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit HealthReport extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthReport" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class HealthReport" />
  <TypeSignature Language="F#" Value="type HealthReport = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.ApplicationHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.ClusterHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.NodeHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.PartitionHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.ServiceHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatelessServiceInstanceHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatefulServiceReplicaHealthReport))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="26374-101">Stellt eine Basisklasse für Integrität Bericht Klassen dar.</span><span class="sxs-lookup"><span data-stu-id="26374-101">Represents a base class for health report classes.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="26374-102">Unterstützten Typen von integritätsberichten sind:<list type="bullet"><item><description><see cref="T:System.Fabric.Health.ApplicationHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.ClusterHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.NodeHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.PartitionHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.ServiceHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.StatelessServiceInstanceHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.StatefulServiceReplicaHealthReport" /></description></item></list></span><span class="sxs-lookup"><span data-stu-id="26374-102">Supported types of health reports are: <list type="bullet"><item><description><see cref="T:System.Fabric.Health.ApplicationHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.ClusterHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.NodeHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.PartitionHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.ServiceHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.StatelessServiceInstanceHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.StatefulServiceReplicaHealthReport" /></description></item></list></span></span></para>
      <para><span data-ttu-id="26374-103">Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="26374-103">The report can be sent to the health store using <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HealthReport (System.Fabric.Health.HealthReportKind kind, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Health.HealthReportKind kind, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthReport.#ctor(System.Fabric.Health.HealthReportKind,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthReport : System.Fabric.Health.HealthReportKind * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.HealthReport" Usage="new System.Fabric.Health.HealthReport (kind, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Health.HealthReportKind" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para><span data-ttu-id="26374-104">Die Art der Integritätsbericht senden.</span><span class="sxs-lookup"><span data-stu-id="26374-104">The kind of the health report.</span></span> </para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="26374-105">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="26374-105">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="26374-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="26374-106">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="26374-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.HealthReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="26374-107">Initializes a new instance of the <see cref="T:System.Fabric.Health.HealthReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthInformation HealthInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthInformation HealthInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthReport.HealthInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthInformation As HealthInformation" />
      <MemberSignature Language="F#" Value="member this.HealthInformation : System.Fabric.Health.HealthInformation" Usage="System.Fabric.Health.HealthReport.HealthInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="26374-108">Ruft die Zustandsinformationen, die allgemeine Integrität Felder beschreibt.</span><span class="sxs-lookup"><span data-stu-id="26374-108">Gets the health information that describes common health fields.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="26374-109">Die Zustandsinformationen, die allgemeine Integrität Felder beschreibt.</span><span class="sxs-lookup"><span data-stu-id="26374-109">The health information that describes common health fields.</span></span></para>
        </value>
        <remarks><span data-ttu-id="26374-110">Die Zustandsinformationen wird beibehalten, im Health Store innerhalb der <see cref="T:System.Fabric.Health.HealthEvent" />.</span><span class="sxs-lookup"><span data-stu-id="26374-110">The health information is persisted in the health store inside the <see cref="T:System.Fabric.Health.HealthEvent" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthReportKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthReportKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthReport.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As HealthReportKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Health.HealthReportKind" Usage="System.Fabric.Health.HealthReport.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthReportKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="26374-111">Ruft die Art des integritätsberichts ab.</span><span class="sxs-lookup"><span data-stu-id="26374-111">Gets the kind of the health report.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="26374-112">Die Art der Integritätsbericht senden.</span><span class="sxs-lookup"><span data-stu-id="26374-112">The kind of the health report.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>