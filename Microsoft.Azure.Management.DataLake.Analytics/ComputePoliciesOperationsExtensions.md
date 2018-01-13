<Type Name="ComputePoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ComputePoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ComputePoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ComputePoliciesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String, parameters As ComputePolicyCreateOrUpdateParameters) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, computePolicyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Konto hinzufügen oder ersetzen die Compute-Richtlinie.
            </param>
        <param name="computePolicyName">
            Der Name der Compute-Richtlinie erstellt oder aktualisiert werden soll.
            </param>
        <param name="parameters">
            Zum Erstellen oder aktualisieren die Compute-Richtlinie angegebenen Parametern. Die Max. Grad an Parallelität pro Auftrag Eigenschaft min Priorität pro Auftrag Eigenschaft oder beides muss vorhanden sein.
            </param>
        <summary>
            Erstellt oder aktualisiert die angegebene Compute-Richtlinie. Während des Updates wird mit dieser neuen Richtlinie für die Berechnung die Compute-Richtlinie mit dem angegebenen Namen ersetzt. Ein Konto unterstützt höchstens 50-Richtlinien
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, computePolicyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Konto hinzufügen oder ersetzen die Compute-Richtlinie.
            </param>
        <param name="computePolicyName">
            Der Name der Compute-Richtlinie erstellt oder aktualisiert werden soll.
            </param>
        <param name="parameters">
            Zum Erstellen oder aktualisieren die Compute-Richtlinie angegebenen Parametern. Die Max. Grad an Parallelität pro Auftrag Eigenschaft min Priorität pro Auftrag Eigenschaft oder beides muss vorhanden sein.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert die angegebene Compute-Richtlinie. Während des Updates wird mit dieser neuen Richtlinie für die Berechnung die Compute-Richtlinie mit dem angegebenen Namen ersetzt. Ein Konto unterstützt höchstens 50-Richtlinien
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Delete (operations, resourceGroupName, accountName, computePolicyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus der die Compute-Richtlinie gelöscht.
            </param>
        <param name="computePolicyName">
            Der Name der Compute-Richtlinie zu löschen.
            </param>
        <summary>
            Löscht die angegebene Compute-Richtlinie aus dem angegebenen Data Lake Analytics-Konto
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, computePolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus der die Compute-Richtlinie gelöscht.
            </param>
        <param name="computePolicyName">
            Der Name der Compute-Richtlinie zu löschen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Compute-Richtlinie aus dem angegebenen Data Lake Analytics-Konto
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Get (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Get(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Get (operations, resourceGroupName, accountName, computePolicyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus der zum Abrufen der Compute-Richtlinie.
            </param>
        <param name="computePolicyName">
            Der Name der abzurufenden Compute-Richtlinie.
            </param>
        <summary>
            Ruft die angegebene Data Lake Analytics-Compute-Richtlinie ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, computePolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus der zum Abrufen der Compute-Richtlinie.
            </param>
        <param name="computePolicyName">
            Der Name der abzurufenden Compute-Richtlinie.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Data Lake Analytics-Compute-Richtlinie ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String) As IPage(Of ComputePolicy)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Konto, von dem die Compute-Richtlinien abgerufen.
            </param>
        <summary>
            Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto. Ein Konto unterstützt höchstens 50-Richtlinien
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Konto, von dem die Compute-Richtlinien abgerufen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto. Ein Konto unterstützt höchstens 50-Richtlinien
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IComputePoliciesOperations, nextPageLink As String) As IPage(Of ComputePolicy)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
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
            Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto. Ein Konto unterstützt höchstens 50-Richtlinien
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
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
            Listet die Data Lake Analytics berechnen Richtlinien in das angegebene Data Lake Analytics-Konto. Ein Konto unterstützt höchstens 50-Richtlinien
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Update (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Update(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String, Optional parameters As ComputePolicy = null) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Update (operations, resourceGroupName, accountName, computePolicyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, das für die Aktualisierung der Compute-Richtlinie.
            </param>
        <param name="computePolicyName">
            Der Name der Compute-Richtlinie aktualisieren.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren der Compute-Richtlinie angegeben werden.
            </param>
        <summary>
            Aktualisiert die angegebene Compute-Richtlinie.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, computePolicyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, das für die Aktualisierung der Compute-Richtlinie.
            </param>
        <param name="computePolicyName">
            Der Name der Compute-Richtlinie aktualisieren.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren der Compute-Richtlinie angegeben werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die angegebene Compute-Richtlinie.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>