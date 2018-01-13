<Type Name="ResourcesOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourcesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ResourcesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginMoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginMoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginMoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.BeginMoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginMoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.BeginMoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;BeginMoveResourcesAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sourceResourceGroupName">
            Quellressourcengruppennamen.
            </param>
        <param name="parameters">
            Verschieben von Ressourcen-Parameter.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verschieben Sie Ressourcen aus einer Ressourcengruppe in einen anderen. Die Ressourcen verschoben wird, sollten alle in der gleichen Ressourcengruppe sein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;CheckExistenceAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="resourceProviderNamespace">
            Identität der Ressource.
            </param>
        <param name="parentResourcePath">
            Identität der Ressource.
            </param>
        <param name="resourceType">
            Identität der Ressource.
            </param>
        <param name="resourceName">
            Identität der Ressource.
            </param>
        <param name="apiVersion"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob die Ressource vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="resourceProviderNamespace">
            Identität der Ressource.
            </param>
        <param name="parentResourcePath">
            Identität der Ressource.
            </param>
        <param name="resourceType">
            Identität der Ressource.
            </param>
        <param name="resourceName">
            Identität der Ressource.
            </param>
        <param name="apiVersion"></param>
        <param name="parameters">
            Erstellen oder Aktualisieren von Ressourcenparametern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie eine Ressource an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="resourceProviderNamespace">
            Identität der Ressource.
            </param>
        <param name="parentResourcePath">
            Identität der Ressource.
            </param>
        <param name="resourceType">
            Identität der Ressource.
            </param>
        <param name="resourceName">
            Identität der Ressource.
            </param>
        <param name="apiVersion"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löschen der Ressource und aller zugehörigen Ressourcen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.GetAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="resourceProviderNamespace">
            Identität der Ressource.
            </param>
        <param name="parentResourcePath">
            Identität der Ressource.
            </param>
        <param name="resourceType">
            Identität der Ressource.
            </param>
        <param name="resourceName">
            Identität der Ressource.
            </param>
        <param name="apiVersion"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt eine Ressource, die in einer Ressourcengruppe gehören.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Alle Ressourcen unter einem Abonnement abgerufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Alle Ressourcen unter einem Abonnement abgerufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.MoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions.MoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourcesOperationsExtensions/&lt;MoveResourcesAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sourceResourceGroupName">
            Quellressourcengruppennamen.
            </param>
        <param name="parameters">
            Verschieben von Ressourcen-Parameter.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verschieben Sie Ressourcen aus einer Ressourcengruppe in einen anderen. Die Ressourcen verschoben wird, sollten alle in der gleichen Ressourcengruppe sein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>