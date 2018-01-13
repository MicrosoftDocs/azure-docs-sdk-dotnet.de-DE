<Type Name="BatchAccountOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BatchAccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BatchAccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BatchAccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BatchAccountOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für BatchAccountOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die den neue Batch-Konto enthält.
            </param>
        <param name="accountName">
            Ein Name für das Batch-Konto muss innerhalb des Bereichs eindeutig sein. Batch-Kontonamen müssen zwischen 3 und 24 Zeichen lang sein und müssen nur aus Ziffern und Kleinbuchstaben verwenden. Dieser Name wird als Teil der DNS-Name verwendet, der verwendet wird, auf die Batch-Dienst in der Region, in dem das Konto erstellt wird. Zum Beispiel: http://accountname.region.batch.azure.com/.
            </param>
        <param name="parameters">
            Zusätzliche Parameter für die Erstellung von Benutzerkonten.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein neues Batch-Konto mit den angegebenen Parametern. Vorhandene Konten können nicht mit dieser API aktualisiert werden, und es stattdessen mit der Update-Batch-Konto-API aktualisiert werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die zu löschenden Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Kontos, das gelöscht werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene Batch-Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; CreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; CreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die den neue Batch-Konto enthält.
            </param>
        <param name="accountName">
            Ein Name für das Batch-Konto muss innerhalb des Bereichs eindeutig sein. Batch-Kontonamen müssen zwischen 3 und 24 Zeichen lang sein und müssen nur aus Ziffern und Kleinbuchstaben verwenden. Dieser Name wird als Teil der DNS-Name verwendet, der verwendet wird, auf die Batch-Dienst in der Region, in dem das Konto erstellt wird. Zum Beispiel: http://accountname.region.batch.azure.com/.
            </param>
        <param name="parameters">
            Zusätzliche Parameter für die Erstellung von Benutzerkonten.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein neues Batch-Konto mit den angegebenen Parametern. Vorhandene Konten können nicht mit dieser API aktualisiert werden, und es stattdessen mit der Update-Batch-Konto-API aktualisiert werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die zu löschenden Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Kontos, das gelöscht werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene Batch-Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; GetAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; GetAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Kontos.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Batch-Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; GetKeysAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; GetKeysAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetKeysAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;GetKeysAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Kontos.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den kontoschlüssel für das angegebene Batch-Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
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
            Ruft Informationen zu den Batch-Konten, die dem Abonnement zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Name der Ressource zu gruppieren, deren Batch-Konten aufgelistet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen zu den Batch-Konten innerhalb der angegebenen Ressourcengruppe verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
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
            Ruft Informationen zu den Batch-Konten innerhalb der angegebenen Ressourcengruppe verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
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
            Ruft Informationen zu den Batch-Konten, die dem Abonnement zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="accountName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SynchronizeAutoStorageKeysAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;SynchronizeAutoStorageKeysAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Synchronisiert die Zugriffsschlüssel für das automatische Speicherkonto an, die für das angegebene Batch-Konto konfiguriert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Kontos.
            </param>
        <param name="parameters">
            Zusätzliche Parameter für das Konto aktualisieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften eines vorhandenen Batch-Kontos.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>