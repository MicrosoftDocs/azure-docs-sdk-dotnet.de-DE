<Type Name="ResourceGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceGroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ResourceGroupsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IResourceGroupsOperations, resourceGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu löschen. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <summary>
            Löscht eine Ressourcengruppe.
            </summary>
        <remarks>
            Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.
            Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu löschen. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.
            Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistence">
      <MemberSignature Language="C#" Value="public static bool CheckExistence (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistence(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistence(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistence (operations As IResourceGroupsOperations, resourceGroupName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistence : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistence (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, um zu überprüfen. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <summary>
            Überprüft, ob eine Ressourcengruppe vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, um zu überprüfen. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob eine Ressourcengruppe vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ResourceGroup) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe erstellt oder aktualisiert werden soll.
            </param>
        <param name="parameters">
            Parameter angegeben wird, auf die erstellen oder Aktualisieren einer Ressourcengruppe.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe erstellt oder aktualisiert werden soll.
            </param>
        <param name="parameters">
            Parameter angegeben wird, auf die erstellen oder Aktualisieren einer Ressourcengruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IResourceGroupsOperations, resourceGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Delete (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu löschen. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <summary>
            Löscht eine Ressourcengruppe.
            </summary>
        <remarks>
            Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.
            Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu löschen. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.
            Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult ExportTemplate (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult ExportTemplate(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplate(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportTemplate (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ExportTemplateRequest) As ResourceGroupExportResult" />
      <MemberSignature Language="F#" Value="static member ExportTemplate : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe als Vorlage zu exportieren.
            </param>
        <param name="parameters">
            Parameter für das Exportieren der Vorlage.
            </param>
        <summary>
            Zeichnet die angegebene Ressourcengruppe als Vorlage.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe als Vorlage zu exportieren.
            </param>
        <param name="parameters">
            Parameter für das Exportieren der Vorlage.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeichnet die angegebene Ressourcengruppe als Vorlage.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Get (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Get(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IResourceGroupsOperations, resourceGroupName As String) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Get (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der abzurufenden Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <summary>
            Ruft eine Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der abzurufenden Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; List (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; List(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IResourceGroupsOperations, Optional odataQuery As ODataQuery(Of ResourceGroupFilter) = null) As IPage(Of ResourceGroup)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <summary>
            Ruft alle Ressourcengruppen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt;" />
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
            Ruft alle Ressourcengruppen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IResourceGroupsOperations, nextPageLink As String) As IPage(Of ResourceGroup)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft alle Ressourcengruppen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
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
            Ruft alle Ressourcengruppen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Update (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Update(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Update(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ResourceGroupPatchable) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Update (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu aktualisieren. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren einer Ressourcengruppe bereitgestellt werden.
            </param>
        <summary>
            Aktualisiert eine Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ressourcengruppen können über einen einfachen Patchvorgang zu einer Gruppenadresse aktualisiert werden. Das Format der Anforderung ist identisch, die zum Erstellen einer Ressourcengruppe. Wenn ein Feld nicht angegeben wird, wird der aktuelle Wert beibehalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; UpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; UpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.UpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu aktualisieren. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren einer Ressourcengruppe bereitgestellt werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ressourcengruppen können über einen einfachen Patchvorgang zu einer Gruppenadresse aktualisiert werden. Das Format der Anforderung ist identisch, die zum Erstellen einer Ressourcengruppe. Wenn ein Feld nicht angegeben wird, wird der aktuelle Wert beibehalten.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>