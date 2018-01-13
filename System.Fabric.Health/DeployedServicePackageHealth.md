<Type Name="DeployedServicePackageHealth" FullName="System.Fabric.Health.DeployedServicePackageHealth">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Die Integrität des ein bereitgestelltes Dienstpaket beschreibt, wie vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedServicePackageHealth.ApplicationName" />
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
          <para>Ruft den Anwendungsnamen, der die Anwendung eindeutig identifiziert.</para>
        </summary>
        <value>
          <para>Der Anwendungsname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedServicePackageHealth.NodeName" />
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
          <para>Ruft ab, dass der Name des Knotens, in dem das Paket bereitgestellten Dienst ausgeführt wird.</para>
        </summary>
        <value>
          <para>Der Knotenname, in dem das Paket bereitgestellten Dienst ausgeführt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Health.DeployedServicePackageHealth.ServiceManifestName" />
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
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Health.DeployedServicePackageHealth.ServicePackageActivationId" />
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
            Ruft die ActivationId der bereitgestelltes Dienstpaket ab.
            </summary>
        <value>
          <para>
            Eine Zeichenfolge von bereitgestelltes Dienstpaket ActivationId darstellt. 
            </para>
          <para>
            Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Health.DeployedServicePackageHealth.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealth.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>