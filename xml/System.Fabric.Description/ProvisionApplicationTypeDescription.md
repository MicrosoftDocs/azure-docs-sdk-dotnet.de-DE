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
      <para><span data-ttu-id="56775-101">Beschreibt einen Anwendungstyp mit bereitzustellenden <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="56775-101">Describes an application type to be provisioned by using <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
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
          <para><span data-ttu-id="56775-102">Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="56775-102">The relative path to the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="56775-103">Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.ProvisionApplicationTypeDescription" />.</span><span class="sxs-lookup"><span data-stu-id="56775-103">Instantiates an instance of <see cref="T:System.Fabric.Description.ProvisionApplicationTypeDescription" />.</span></span></para>
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
          <para><span data-ttu-id="56775-104">Ruft ab oder legt das Flag, das angibt, ob die Bereitstellung asynchron erfolgen soll.</span><span class="sxs-lookup"><span data-stu-id="56775-104">Gets or sets the flag indicating whether provisioning should occur asynchronously.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56775-105">Wenn dieses Flag auf "false" festgelegt ist, und klicken Sie dann das Verhalten dem Aufruf entspricht <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="56775-105">If this flag is false, then the behavior is equivalent to calling <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span> <span data-ttu-id="56775-106">Der Timeout-Argument auf der Bereitstellungsvorgang selbst angewendet wird, und die zurückgegebene Aufgabe abgeschlossen ist, nur wenn der Bereitstellungsvorgang im System abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="56775-106">The timeout argument is applied to the provision operation itself and the returned task completes only when the provision operation completes in the system.</span></span></para>
          <para><span data-ttu-id="56775-107">Wenn dieses Flag "true ist", klicken Sie dann das Timeout-Argument nur, um die Nachrichtenübermittlung angewendet wird und die zurückgegebene Aufgabe abgeschlossen, einmal ist hat das System die Anforderung akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="56775-107">If this flag is true, then the timeout argument is only applied to message delivery and the returned task completes once the system has accepted the request.</span></span>
            <span data-ttu-id="56775-108">Das System verarbeitet, der Bereitstellungsvorgang alle unbegrenztes Timeout und seinen Status kann abgefragt werden, mithilfe von <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />.</span><span class="sxs-lookup"><span data-stu-id="56775-108">The system will process the provision operation without any timeout limit and its state can be queried using <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />.</span></span>
            <span data-ttu-id="56775-109">Der ausstehende Bereitstellungsvorgang kann unterbrochen werden, mithilfe von <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="56775-109">The pending provision operation can be interrupted using <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String)" />.</span></span></para>
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
          <para><span data-ttu-id="56775-110">Ruft den relativen Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="56775-110">Gets the relative path to the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56775-111">Der Pfad der Anwendung Pakets-Build.</span><span class="sxs-lookup"><span data-stu-id="56775-111">The application package build path.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>