<Type Name="DeployedServicePackage" FullName="System.Fabric.Query.DeployedServicePackage">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServicePackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackage" />
  <TypeSignature Language="F#" Value="type DeployedServicePackage = class" />
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
      <para>
            Beschreibt ein bereitgestelltes Dienstpaket an. Dies kann mithilfe der Abfrage abgerufen werden <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> das Zurückgeben einer Liste von <see cref="T:System.Fabric.Query.DeployedServicePackage" /> auf einem bestimmten Knoten.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeployedServicePackageStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.DeploymentStatus DeployedServicePackageStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.DeploymentStatus DeployedServicePackageStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.DeployedServicePackageStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageStatus As DeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageStatus : System.Fabric.DeploymentStatus" Usage="System.Fabric.Query.DeployedServicePackage.DeployedServicePackageStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Paketstatus bereitgestellten Dienst ab.</para>
        </summary>
        <value>
          <para>Der Status des bereitgestellten Dienstpakets.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedServicePackage.ServiceManifestName" />
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
          <para>Ruft den Namen des Dienst-Manifests ab.</para>
        </summary>
        <value>
          <para>Der dienstmanifestname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string ServiceManifestVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.ServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestVersion : string" Usage="System.Fabric.Query.DeployedServicePackage.ServiceManifestVersion" />
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
          <para>Ruft die dienstmanifestversion ab.</para>
        </summary>
        <value>
          <para>Die dienstmanifestversion.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />
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
            Ruft die ActivationId des Dienstpakets ab.
            </summary>
        <value>
          <para>
            Eine Zeichenfolge von bereitgestelltes Dienstpaket ActivationId darstellt. Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>