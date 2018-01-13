<Type Name="SubscriptionDefinitionsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionDefinitionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsOperationsExtensions = class" />
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
            Erweiterungsmethoden für SubscriptionDefinitionsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition BeginCreate (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition BeginCreate(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String, body As SubscriptionDefinition) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreate (operations, subscriptionDefinitionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="subscriptionDefinitionName">
            Der Name der Definition des Azure-Abonnement.
            </param>
        <param name="body">
            Die Erstellung des Abonnements Definition.
            </param>
        <summary>
            Erstellen Sie die Definition einer Azure-Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; BeginCreateAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; BeginCreateAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreateAsync (operations, subscriptionDefinitionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="subscriptionDefinitionName">
            Der Name der Definition des Azure-Abonnement.
            </param>
        <param name="body">
            Die Erstellung des Abonnements Definition.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie die Definition einer Azure-Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Create (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Create(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Create(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String, body As SubscriptionDefinition) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Create (operations, subscriptionDefinitionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="subscriptionDefinitionName">
            Der Name der Definition des Azure-Abonnement.
            </param>
        <param name="body">
            Die Erstellung des Abonnements Definition.
            </param>
        <summary>
            Erstellen Sie die Definition einer Azure-Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; CreateAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; CreateAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.CreateAsync (operations, subscriptionDefinitionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="subscriptionDefinitionName">
            Der Name der Definition des Azure-Abonnement.
            </param>
        <param name="body">
            Die Erstellung des Abonnements Definition.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie die Definition einer Azure-Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Get (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Get(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Get (operations, subscriptionDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="subscriptionDefinitionName">
            Der Name der Definition des Azure-Abonnement.
            </param>
        <summary>
            Rufen Sie die Definition einer Azure-Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetAsync (operations, subscriptionDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="subscriptionDefinitionName">
            Der Name der Definition des Azure-Abonnement.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie die Definition einer Azure-Abonnement.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition GetOperationStatus (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition GetOperationStatus(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatus(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatus (operations As ISubscriptionDefinitionsOperations, operationId As Guid) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member GetOperationStatus : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * Guid -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatus (operations, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="operationId">
            Die Vorgangs-ID, die im Antwortheader generieren Empfehlung aus dem Feld "Speicherort" befinden.
            </param>
        <summary>
            Ruft den Status der Abonnementdefinition PUT-Vorgang ab. Der URI dieser API wird in das Feld "Speicherort" in der Antwortheader zurückgegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetOperationStatusAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, Guid operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetOperationStatusAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatusAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOperationStatusAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatusAsync (operations, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;GetOperationStatusAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="operationId">
            Die Vorgangs-ID, die im Antwortheader generieren Empfehlung aus dem Feld "Speicherort" befinden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den Status der Abonnementdefinition PUT-Vorgang ab. Der URI dieser API wird in das Feld "Speicherort" in der Antwortheader zurückgegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; List (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; List(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISubscriptionDefinitionsOperations) As IPage(Of SubscriptionDefinition)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Auflisten der Definition einer Azure-Abonnement "subscriptionId".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Auflisten der Definition einer Azure-Abonnement "subscriptionId".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISubscriptionDefinitionsOperations, nextPageLink As String) As IPage(Of SubscriptionDefinition)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
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
            Auflisten der Definition einer Azure-Abonnement "subscriptionId".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
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
            Auflisten der Definition einer Azure-Abonnement "subscriptionId".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>