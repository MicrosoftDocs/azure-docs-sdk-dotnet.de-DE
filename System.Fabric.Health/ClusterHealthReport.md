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
      <para>Stellt einen Statusbericht für die Cluster-Integrität-Entität verwendet werden soll.</para>
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
          <para>Der Integritätsinformationen der Berichtsparameter beschrieben wird. Darf nicht NULL sein.</para>
        </param>
        <summary>
          <para>Erstellt einen Statusbericht für den Cluster.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>