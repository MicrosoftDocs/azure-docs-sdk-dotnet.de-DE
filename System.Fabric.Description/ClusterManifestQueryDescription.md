<Type Name="ClusterManifestQueryDescription" FullName="System.Fabric.Description.ClusterManifestQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterManifestQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterManifestQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterManifestQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterManifestQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterManifestQueryDescription = class" />
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
            Beschreibt die Abfrageparameter für die Verwendung mit <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.Fabric.Description.ClusterManifestQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterManifestQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterManifestQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Konstrukte Abfrageparameter zum Abrufen des Inhalts von einem clustermanifest.
            </para>
        </summary>
        <remarks>
          <para>
            Standardmäßig wird der aktuelle ausgeführten clustermanifest abgerufen werden. Zum Abfragen von einem anderen clustermanifestversion, die zuvor bereitgestellt wurde mit <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String)" />, geben Sie die gewünschte Abfrage Version mit <see cref="P:System.Fabric.Description.ClusterManifestQueryDescription.ClusterManifestVersion" />.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterManifestVersion">
      <MemberSignature Language="C#" Value="public string ClusterManifestVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterManifestQueryDescription.ClusterManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ClusterManifestVersion : string with get, set" Usage="System.Fabric.Description.ClusterManifestQueryDescription.ClusterManifestVersion" />
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
          <para>
            Ruft ab oder legt die Version von clustermanifest abgerufen.
            </para>
        </summary>
        <value>
          <para>Die Version des clustermanifest.</para>
        </value>
        <remarks>
          <para>
            Auf Null (Standardeinstellung) oder eine leere Zeichenfolge festgelegt, werden die aktuellen ausgeführten clustermanifest abgerufen.
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>