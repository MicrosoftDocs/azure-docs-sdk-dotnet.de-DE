<Type Name="NodeHealthReport" FullName="System.Fabric.Health.NodeHealthReport">
  <TypeSignature Language="C#" Value="public class NodeHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type NodeHealthReport = class&#xA;    inherit HealthReport" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthReport</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="d88de-101">Stellt einen Statusbericht auf die Knoten Integrität Entität angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="d88de-101">Represents a health report to be applied on the node health entity.</span></span> <span data-ttu-id="d88de-102">Der Bericht wird gesendet, in Health Store mit <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="d88de-102">The report is sent to health store with <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthReport (string nodeName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthReport.#ctor(System.String,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.NodeHealthReport : string * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.NodeHealthReport" Usage="new System.Fabric.Health.NodeHealthReport (nodeName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="d88de-103">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="d88de-103">The node name.</span></span> <span data-ttu-id="d88de-104">Darf nicht null oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="d88de-104">Can’t be null or empty.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="d88de-105">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="d88de-105">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="d88de-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d88de-106">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="d88de-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.NodeHealthReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d88de-107">Initializes a new instance of the <see cref="T:System.Fabric.Health.NodeHealthReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="d88de-108">Integritätsinformationen darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="d88de-108">Health information can’t be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="d88de-109">Knotenname darf nicht leer sein.</span><span class="sxs-lookup"><span data-stu-id="d88de-109">Node name can’t be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthReport.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.NodeHealthReport.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d88de-110">Ruft den Knotennamen ab.</span><span class="sxs-lookup"><span data-stu-id="d88de-110">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d88de-111">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="d88de-111">The node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>