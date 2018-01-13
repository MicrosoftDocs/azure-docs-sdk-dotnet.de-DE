<Type Name="ITableControllerConfigProvider" FullName="Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider">
  <TypeSignature Language="C#" Value="public interface ITableControllerConfigProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITableControllerConfigProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITableControllerConfigProvider" />
  <TypeSignature Language="F#" Value="type ITableControllerConfigProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="88318-101">Stellt eine Abstraktion zum Ausführen von Anpassungen der Konfiguration für <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" /> Controller abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="88318-101">Provides an abstraction for performing configuration customizations for <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" /> derived controllers.</span></span> <span data-ttu-id="88318-102">Eine Implementierung registriert werden kann, über die <see cref="T:System.Web.Http.HttpConfiguration" />.</span><span class="sxs-lookup"><span data-stu-id="88318-102">An implementation can be registered via the <see cref="T:System.Web.Http.HttpConfiguration" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public void Configure (System.Web.Http.Controllers.HttpControllerSettings controllerSettings, System.Web.Http.Controllers.HttpControllerDescriptor controllerDescriptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Configure(class System.Web.Http.Controllers.HttpControllerSettings controllerSettings, class System.Web.Http.Controllers.HttpControllerDescriptor controllerDescriptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider.Configure(System.Web.Http.Controllers.HttpControllerSettings,System.Web.Http.Controllers.HttpControllerDescriptor)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Configure (controllerSettings As HttpControllerSettings, controllerDescriptor As HttpControllerDescriptor)" />
      <MemberSignature Language="F#" Value="abstract member Configure : System.Web.Http.Controllers.HttpControllerSettings * System.Web.Http.Controllers.HttpControllerDescriptor -&gt; unit" Usage="iTableControllerConfigProvider.Configure (controllerSettings, controllerDescriptor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="controllerSettings" Type="System.Web.Http.Controllers.HttpControllerSettings" />
        <Parameter Name="controllerDescriptor" Type="System.Web.Http.Controllers.HttpControllerDescriptor" />
      </Parameters>
      <Docs>
        <param name="controllerSettings"><span data-ttu-id="88318-103">Die <see cref="T:System.Web.Http.Controllers.HttpControllerSettings" /> für diesen Controller.</span><span class="sxs-lookup"><span data-stu-id="88318-103">The <see cref="T:System.Web.Http.Controllers.HttpControllerSettings" /> for this controller type.</span></span></param>
        <param name="controllerDescriptor"><span data-ttu-id="88318-104">Die <see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" /> für diesen Controller.</span><span class="sxs-lookup"><span data-stu-id="88318-104">The <see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" /> for this controller type.</span></span></param>
        <summary>
            <span data-ttu-id="88318-105">Konfiguriert die spezifischen Einstellungen für Controller vom Typ <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span><span class="sxs-lookup"><span data-stu-id="88318-105">Configures the settings specific for controllers of type <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>