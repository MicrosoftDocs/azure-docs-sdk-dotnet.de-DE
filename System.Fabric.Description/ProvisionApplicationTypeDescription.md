<Type Name="ProvisionApplicationTypeDescription" FullName="System.Fabric.Description.ProvisionApplicationTypeDescription">
  <TypeSignature Language="C#" Value="public sealed class ProvisionApplicationTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ProvisionApplicationTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ProvisionApplicationTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ProvisionApplicationTypeDescription" />
  <TypeSignature Language="F#" Value="type ProvisionApplicationTypeDescription = class" />
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
      <para>Beschreibt einen Anwendungstyp mit bereitzustellenden <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProvisionApplicationTypeDescription (string buildPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string buildPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ProvisionApplicationTypeDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buildPath As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ProvisionApplicationTypeDescription : string -&gt; System.Fabric.Description.ProvisionApplicationTypeDescription" Usage="new System.Fabric.Description.ProvisionApplicationTypeDescription buildPath" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buildPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="buildPath">
          <para>Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</para>
        </param>
        <summary>
          <para>Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.ProvisionApplicationTypeDescription" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Async">
      <MemberSignature Language="C#" Value="public bool Async { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Async" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ProvisionApplicationTypeDescription.Async" />
      <MemberSignature Language="VB.NET" Value="Public Property Async As Boolean" />
      <MemberSignature Language="F#" Value="member this.Async : bool with get, set" Usage="System.Fabric.Description.ProvisionApplicationTypeDescription.Async" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Flag, das angibt, ob die Bereitstellung asynchron erfolgen soll.</para>
        </summary>
        <value>
          <para>Wenn dieses Flag auf "false" festgelegt ist, und klicken Sie dann das Verhalten dem Aufruf entspricht <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />. Der Timeout-Argument auf der Bereitstellungsvorgang selbst angewendet wird, und die zurückgegebene Aufgabe abgeschlossen ist, nur wenn der Bereitstellungsvorgang im System abgeschlossen ist.</para>
          <para>Wenn dieses Flag "true ist", klicken Sie dann das Timeout-Argument nur, um die Nachrichtenübermittlung angewendet wird und die zurückgegebene Aufgabe abgeschlossen, einmal ist hat das System die Anforderung akzeptiert.
            Das System verarbeitet, der Bereitstellungsvorgang alle unbegrenztes Timeout und seinen Status kann abgefragt werden, mithilfe von <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />.
            Der ausstehende Bereitstellungsvorgang kann unterbrochen werden, mithilfe von <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String)" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildPath">
      <MemberSignature Language="C#" Value="public string BuildPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BuildPath" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ProvisionApplicationTypeDescription.BuildPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BuildPath As String" />
      <MemberSignature Language="F#" Value="member this.BuildPath : string" Usage="System.Fabric.Description.ProvisionApplicationTypeDescription.BuildPath" />
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
          <para>Ruft den relativen Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</para>
        </summary>
        <value>
          <para>Der Pfad der Anwendung Pakets-Build.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>