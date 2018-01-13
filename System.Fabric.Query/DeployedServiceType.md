<Type Name="DeployedServiceType" FullName="System.Fabric.Query.DeployedServiceType">
  <TypeSignature Language="C#" Value="public sealed class DeployedServiceType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServiceType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServiceType" />
  <TypeSignature Language="F#" Value="type DeployedServiceType = class" />
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
      <para>Stellt einen bereitgestellten Dienst dar.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Query.DeployedServiceType.CodePackageName" />
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
          <para>Ruft den Namen der Code-Paket.</para>
        </summary>
        <value>
          <para>Der Paketname für den Code.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedServiceType.ServiceManifestName" />
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
          <para>Der Name des im Dienstmanifest.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />
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
            Eine Zeichenfolge von bereitgestelltes Dienstpaket ActivationId darstellt. Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Query.DeployedServiceType.ServiceTypeName" />
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
          <para>Ruft den Typnamen des Dienstes ab.</para>
        </summary>
        <value>
          <para>Den Namen des Diensttyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeRegistrationStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceTypeRegistrationStatus ServiceTypeRegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceTypeRegistrationStatus ServiceTypeRegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceTypeRegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeRegistrationStatus As ServiceTypeRegistrationStatus" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeRegistrationStatus : System.Fabric.Query.ServiceTypeRegistrationStatus" Usage="System.Fabric.Query.DeployedServiceType.ServiceTypeRegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceTypeRegistrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Registrierungsstatus des Dienst-Typ ab.</para>
        </summary>
        <value>
          <para>Der Status der dienstregistrierung geben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>