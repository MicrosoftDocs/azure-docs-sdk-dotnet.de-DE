<Type Name="ClusterHealthReport" FullName="System.Fabric.Health.ClusterHealthReport">
  <TypeSignature Language="C#" Value="public class ClusterHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type ClusterHealthReport = class&#xA;    inherit HealthReport" />
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
      <para><span data-ttu-id="e7206-101">Stellt einen Statusbericht für die Cluster-Integrität-Entität verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="e7206-101">Represents a health report to be applied on the cluster health entity.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthReport (System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthReport.#ctor(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.ClusterHealthReport : System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.ClusterHealthReport" Usage="new System.Fabric.Health.ClusterHealthReport healthInformation" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInformation">
          <para><span data-ttu-id="e7206-102">Der Integritätsinformationen der Berichtsparameter beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="e7206-102">The health information which describes the report parameters.</span></span> <span data-ttu-id="e7206-103">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="e7206-103">Cannot be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7206-104">Erstellt einen Statusbericht für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="e7206-104">Creates a cluster health report.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="e7206-105">Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="e7206-105">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>