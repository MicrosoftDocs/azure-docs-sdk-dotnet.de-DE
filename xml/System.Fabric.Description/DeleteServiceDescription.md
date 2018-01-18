<Type Name="DeleteServiceDescription" FullName="System.Fabric.Description.DeleteServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class DeleteServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeleteServiceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeleteServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeleteServiceDescription" />
  <TypeSignature Language="F#" Value="type DeleteServiceDescription = class" />
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
      <para><span data-ttu-id="cff2d-101">Beschreibt einen Dienst zu mit zu löschenden <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="cff2d-101">Describes an service to be deleted by using <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteServiceDescription (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeleteServiceDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeleteServiceDescription : Uri -&gt; System.Fabric.Description.DeleteServiceDescription" Usage="new System.Fabric.Description.DeleteServiceDescription serviceName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="cff2d-102">Der URI des Dienstnamens Instanz.</span><span class="sxs-lookup"><span data-stu-id="cff2d-102">URI of the service instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="cff2d-103">Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.DeleteServiceDescription" />.</span><span class="sxs-lookup"><span data-stu-id="cff2d-103">Instantiates an instance of <see cref="T:System.Fabric.Description.DeleteServiceDescription" />.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceDelete">
      <MemberSignature Language="C#" Value="public bool ForceDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceDelete" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteServiceDescription.ForceDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceDelete As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceDelete : bool with get, set" Usage="System.Fabric.Description.DeleteServiceDescription.ForceDelete" />
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
          <para><span data-ttu-id="cff2d-104">Ruft das Flag, die angibt, ob der Dienst soll Möglichkeit gewährt werden, die der Zustand ordnungsgemäß bereinigt und schließen Sie ab.</span><span class="sxs-lookup"><span data-stu-id="cff2d-104">Gets the flag that specifies whether the service should be given a chance to gracefully clean up its state and close.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cff2d-105">Flag, die angibt, ob der Dienst sich auf dessen Status und schließen ordnungsgemäß bereinigen gewährt werden soll.</span><span class="sxs-lookup"><span data-stu-id="cff2d-105">Flag that specifies whether the service should be given a chance to gracefully clean up its state and close.</span></span></para>
          <para><span data-ttu-id="cff2d-106">Wenn das ForceDelete-Flag wird festgelegt, wird der Dienst wird nicht ordnungsgemäß geschlossen werden, und zustandsbehaftete Dienste Offenlegung von können persistente Status auf.</span><span class="sxs-lookup"><span data-stu-id="cff2d-106">If the ForceDelete flag is set then the service won't be closed gracefully and stateful services may leak persisted state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteServiceDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.DeleteServiceDescription.ServiceName" />
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
          <para><span data-ttu-id="cff2d-107">Ruft den Namen der URI der Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="cff2d-107">Gets the URI name of the service instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cff2d-108">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="cff2d-108">The service name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>