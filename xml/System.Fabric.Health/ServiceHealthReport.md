<Type Name="ServiceHealthReport" FullName="System.Fabric.Health.ServiceHealthReport">
  <TypeSignature Language="C#" Value="public class ServiceHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type ServiceHealthReport = class&#xA;    inherit HealthReport" />
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
      <para><span data-ttu-id="49477-101">Stellt einen Statusbericht auf eine Service Health Entität angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="49477-101">Represents a health report to be applied on a service health entity.</span></span>
            <span data-ttu-id="49477-102">Der Bericht wird gesendet, in Health Store mit <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="49477-102">The report is sent to health store with <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthReport (Uri serviceName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri serviceName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthReport.#ctor(System.Uri,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.ServiceHealthReport : Uri * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.ServiceHealthReport" Usage="new System.Fabric.Health.ServiceHealthReport (serviceName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="49477-103">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="49477-103">The service name.</span></span> <span data-ttu-id="49477-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="49477-104">Required.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="49477-105">Die HealthInformation, die die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus beschreibt.</span><span class="sxs-lookup"><span data-stu-id="49477-105">The HealthInformation which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="49477-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="49477-106">Required.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="49477-107">Initialisiert eine neue Instanz von <see cref="T:System.Fabric.Health.ServiceHealthReport" />.</span><span class="sxs-lookup"><span data-stu-id="49477-107">Initializes a new instance of <see cref="T:System.Fabric.Health.ServiceHealthReport" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="49477-108">Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="49477-108">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthReport.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealthReport.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="49477-109">Ruft den Namen des Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="49477-109">Gets the name of the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="49477-110">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="49477-110">The name of the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>