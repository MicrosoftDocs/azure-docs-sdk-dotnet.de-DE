<Type Name="TableFilterProvider" FullName="Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider">
  <TypeSignature Language="C#" Value="public class TableFilterProvider : System.Web.Http.Filters.IFilterProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableFilterProvider extends System.Object implements class System.Web.Http.Filters.IFilterProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class TableFilterProvider&#xA;Implements IFilterProvider" />
  <TypeSignature Language="F#" Value="type TableFilterProvider = class&#xA;    interface IFilterProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Web.Http.Filters.IFilterProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ec56a-101">Die <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" /> spezielle Register <see cref="T:System.Web.Http.Filters.IActionFilter" /> Instanzen mit dem <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span><span class="sxs-lookup"><span data-stu-id="ec56a-101">The <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" /> registers specialized <see cref="T:System.Web.Http.Filters.IActionFilter" /> instances used by the <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span></span> <span data-ttu-id="ec56a-102">Die Filter werden im Rahmen der benutzerdefinierten Controller-Konfiguration, die mithilfe des Dependency Injection-Moduls unter Verwendung des Datentyps konfiguriert werden können registriert <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" />.</span><span class="sxs-lookup"><span data-stu-id="ec56a-102">The filters are registered as part of the custom controller configuration which can be configured using the dependency injection engine using the type <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableFilterProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec56a-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" /> unter Verwendung des standardmäßigen <see cref="T:System.Web.Http.QueryableAttribute" /> Implementierung für die Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="ec56a-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" /> using the default <see cref="T:System.Web.Http.QueryableAttribute" /> implementation for executing the query.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableFilterProvider (System.Web.Http.Filters.IActionFilter queryFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Web.Http.Filters.IActionFilter queryFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider.#ctor(System.Web.Http.Filters.IActionFilter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queryFilter As IActionFilter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider : System.Web.Http.Filters.IActionFilter -&gt; Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" Usage="new Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider queryFilter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queryFilter" Type="System.Web.Http.Filters.IActionFilter" />
      </Parameters>
      <Docs>
        <param name="queryFilter">To be added.</param>
        <summary>
            <span data-ttu-id="ec56a-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" /> unter Verwendung der angegebenen <see cref="T:System.Web.Http.QueryableAttribute" /> Implementierung für die Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="ec56a-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider" /> using the provided <see cref="T:System.Web.Http.QueryableAttribute" /> implementation for executing the query.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;System.Web.Http.Filters.FilterInfo&gt; GetFilters (System.Web.Http.HttpConfiguration configuration, System.Web.Http.Controllers.HttpActionDescriptor actionDescriptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class System.Web.Http.Filters.FilterInfo&gt; GetFilters(class System.Web.Http.HttpConfiguration configuration, class System.Web.Http.Controllers.HttpActionDescriptor actionDescriptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableFilterProvider.GetFilters(System.Web.Http.HttpConfiguration,System.Web.Http.Controllers.HttpActionDescriptor)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetFilters (configuration As HttpConfiguration, actionDescriptor As HttpActionDescriptor) As IEnumerable(Of FilterInfo)" />
      <MemberSignature Language="F#" Value="abstract member GetFilters : System.Web.Http.HttpConfiguration * System.Web.Http.Controllers.HttpActionDescriptor -&gt; seq&lt;System.Web.Http.Filters.FilterInfo&gt;&#xA;override this.GetFilters : System.Web.Http.HttpConfiguration * System.Web.Http.Controllers.HttpActionDescriptor -&gt; seq&lt;System.Web.Http.Filters.FilterInfo&gt;" Usage="tableFilterProvider.GetFilters (configuration, actionDescriptor)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Web.Http.Filters.IFilterProvider.GetFilters(System.Web.Http.HttpConfiguration,System.Web.Http.Controllers.HttpActionDescriptor)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Web.Http.Filters.FilterInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configuration" Type="System.Web.Http.HttpConfiguration" />
        <Parameter Name="actionDescriptor" Type="System.Web.Http.Controllers.HttpActionDescriptor" />
      </Parameters>
      <Docs>
        <param name="configuration">To be added.</param>
        <param name="actionDescriptor">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
  </Members>
</Type>