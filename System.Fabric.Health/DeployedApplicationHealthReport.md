<Type Name="DeployedApplicationHealthReport" FullName="System.Fabric.Health.DeployedApplicationHealthReport">
  <TypeSignature Language="C#" Value="public class DeployedApplicationHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeployedApplicationHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class DeployedApplicationHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthReport = class&#xA;    inherit HealthReport" />
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
      <para>Stellt einen Statusbericht für die bereitgestellte Anwendung Integritäts-Entität verwendet werden soll. </para>
    </summary>
    <remarks>Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthReport (Uri applicationName, string nodeName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthReport.#ctor(System.Uri,System.String,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.DeployedApplicationHealthReport : Uri * string * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.DeployedApplicationHealthReport" Usage="new System.Fabric.Health.DeployedApplicationHealthReport (applicationName, nodeName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname. Darf nicht NULL sein.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname. Darf weder NULL noch leer sein.</para>
        </param>
        <param name="healthInformation">
          <para>Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus. Darf nicht NULL sein.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedApplicationHealthReport" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>
            <paramref name="healthInformation" /> darf nicht NULL sein.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
            <paramref name="nodeName" />darf nicht leer sein.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthReport.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedApplicationHealthReport.ApplicationName" />
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
          <para>Ruft den Namen der Anwendung ab.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Uri" /> , die den Namen der Anwendung darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthReport.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealthReport.NodeName" />
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
          <para>Ruft ab, dass der Name des Knotens, in dem die bereitgestellte Anwendung ausgeführt wird.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.String" /> , der Name des Knotens darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>