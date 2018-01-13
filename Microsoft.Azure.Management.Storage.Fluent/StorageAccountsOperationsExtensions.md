<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für StorageAccountsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="accountName">
            Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.
            Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.
            </param>
        <param name="parameters">
            Die Parameter für das erstellte Konto bereitstellen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.
            Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden. Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="name"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob der Name des Speicherkontos ist gültig und wird nicht bereits verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="accountName">
            Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.
            Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.
            </param>
        <param name="parameters">
            Die Parameter für das erstellte Konto bereitstellen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.
            Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden. Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="accountName">
            Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.
            Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Speicherkonto in Microsoft Azure.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;GetPropertiesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="accountName">
            Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.
            Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Die Eigenschaften für das angegebene Speicherkonto einschließlich, aber nicht beschränkt auf Name, SKU-Name, Speicherort und Kontostatus zurückgegeben. Der ListKeys-Vorgang sollte verwendet werden, um Speicherschlüssel abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
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
            Listet alle Speicherkonten im Abonnement verfügbar. Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Speicherkonten verfügbar sind, unter der angegebenen Ressourcengruppe.
            Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListKeysAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="accountName">
            Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.
            Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Zugriffsschlüssel für das angegebene Speicherkonto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="accountName">
            Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.
            Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.
            </param>
        <param name="keyName"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Generiert eine die Zugriffsschlüssel für das angegebene Speicherkonto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="accountName">
            Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.
            Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.
            </param>
        <param name="parameters">
            Die Parameter für die aktualisierte Konto bereitstellen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Update-Vorgang kann verwendet werden, um die SKU, Verschlüsselung, zugriffstarifs oder Tags für ein Speicherkonto zu aktualisieren. Es kann auch verwendet werden, um das Konto zu einer benutzerdefinierten Domäne zuzuordnen. Nur eine benutzerdefinierte Domäne wird pro Speicherkonto unterstützt. die Ersetzung/Änderung der benutzerdefinierten Domäne wird nicht unterstützt. Um eine alte benutzerdefinierte Domäne zu ersetzen, muss der alte Wert gelöscht/aufgehoben werden bevor ein neuer Wert festgelegt werden kann. Das Update von mehreren Eigenschaften wird unterstützt. Dieser Aufruf wird der Speicherschlüssel für das Konto nicht geändert. Wenn Sie die speicherkontoschlüssel ändern möchten, verwenden Sie die Schlüssel neu generieren-Vorgang. Der Speicherort und den Namen des Speicherkontos können nach der Erstellung nicht geändert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>