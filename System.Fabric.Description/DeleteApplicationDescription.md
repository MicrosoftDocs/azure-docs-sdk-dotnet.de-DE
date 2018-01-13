<Type Name="DeleteApplicationDescription" FullName="System.Fabric.Description.DeleteApplicationDescription">
  <TypeSignature Language="C#" Value="public sealed class DeleteApplicationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeleteApplicationDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeleteApplicationDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeleteApplicationDescription" />
  <TypeSignature Language="F#" Value="type DeleteApplicationDescription = class" />
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
      <para><span data-ttu-id="c7dcf-101">Beschreibt eine Anwendung mit zu löschenden <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-101">Describes an application to be deleted by using <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteApplicationDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeleteApplicationDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeleteApplicationDescription : Uri -&gt; System.Fabric.Description.DeleteApplicationDescription" Usage="new System.Fabric.Description.DeleteApplicationDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c7dcf-102">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-102">URI of the application instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c7dcf-103">Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.DeleteApplicationDescription" />.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-103">Instantiates an instance of <see cref="T:System.Fabric.Description.DeleteApplicationDescription" />.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteApplicationDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeleteApplicationDescription.ApplicationName" />
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
          <para><span data-ttu-id="c7dcf-104">Ruft den URI-Namen der Anwendungsinstanz.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-104">Gets the URI name of the application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c7dcf-105">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-105">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceDelete">
      <MemberSignature Language="C#" Value="public bool ForceDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceDelete" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteApplicationDescription.ForceDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceDelete As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceDelete : bool with get, set" Usage="System.Fabric.Description.DeleteApplicationDescription.ForceDelete" />
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
          <para><span data-ttu-id="c7dcf-106">Ruft ab oder legt das Flag, die angibt, ob die Anwendung soll Möglichkeit gewährt werden, die ordnungsgemäß bereinigen Sie seinen Status und zu schließen.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-106">Gets or sets the flag that specifies whether the application should be given a chance to gracefully clean up its state and close.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c7dcf-107">Flag, die angibt, ob die Anwendung Gelegenheit, dessen Status und schließen ordnungsgemäß bereinigen gewährt werden soll.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-107">Flag that specifies whether the application should be given a chance to gracefully clean up its state and close.</span></span></para>
          <para><span data-ttu-id="c7dcf-108">Wenn das ForceDelete-Flag festgelegt ist, und klicken Sie dann die Anwendung nicht ordnungsgemäß geschlossen und zustandsbehaftete Dienste darin Offenlegung von können beibehalten Zustand auf.</span><span class="sxs-lookup"><span data-stu-id="c7dcf-108">If the ForceDelete flag is set then the application won't be closed gracefully and stateful services in it may leak persisted state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>