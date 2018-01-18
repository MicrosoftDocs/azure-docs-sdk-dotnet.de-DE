<Type Name="ApplicationHealthReport" FullName="System.Fabric.Health.ApplicationHealthReport">
  <TypeSignature Language="C#" Value="public class ApplicationHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type ApplicationHealthReport = class&#xA;    inherit HealthReport" />
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
      <para><span data-ttu-id="10f36-101">Stellt einen Statusbericht auf einem Anwendungsserver-Entität Health angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="10f36-101">Represents a health report to be applied on an application health entity.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="10f36-102">Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="10f36-102">The report can be sent to the health store using <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthReport (Uri applicationName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthReport.#ctor(System.Uri,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.ApplicationHealthReport : Uri * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.ApplicationHealthReport" Usage="new System.Fabric.Health.ApplicationHealthReport (applicationName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="10f36-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="10f36-103">The application name.</span></span> <span data-ttu-id="10f36-104">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="10f36-104">Cannot be null.</span></span></para>
        </param>
        <param name="healthInformation">
          <para><span data-ttu-id="10f36-105">Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="10f36-105">The <see cref="T:System.Fabric.Health.HealthInformation" /> which describes the report fields, like sourceId, property, health state.</span></span> <span data-ttu-id="10f36-106">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="10f36-106">Cannot be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="10f36-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ApplicationHealthReport" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="10f36-107">Initializes a new instance of the <see cref="T:System.Fabric.Health.ApplicationHealthReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="10f36-108">Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="10f36-108">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthReport.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealthReport.ApplicationName" />
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
          <para><span data-ttu-id="10f36-109">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="10f36-109">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="10f36-110">Die <see cref="T:System.Uri" /> , die den Namen der Anwendung darstellt.</span><span class="sxs-lookup"><span data-stu-id="10f36-110">The <see cref="T:System.Uri" /> representing the application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>