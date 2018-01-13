<Type Name="NamespacesOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NamespacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NamespacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NamespacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NamespacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für NamespacesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDelete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <summary>
            Löscht einen vorhandenen Namespace. Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen vorhandenen Namespace. Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As INamespacesOperations, parameters As CheckAvailabilityParameters) As CheckAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            Der Namespacename.
            </param>
        <summary>
            Überprüft die Verfügbarkeit des angegebenen Dienstnamespace über alle Azure-Abonnements. Dies ist hilfreich, da der Domänenname basierend auf den Dienstnamespace erstellt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            Der Namespacename.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft die Verfügbarkeit des angegebenen Dienstnamespace über alle Azure-Abonnements. Dies ist hilfreich, da der Domänenname basierend auf den Dienstnamespace erstellt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource CreateOrUpdate (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource CreateOrUpdate(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As NamespaceCreateOrUpdateParameters) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="parameters">
            Parameter, die zum Erstellen einer Ressource Namespace angegeben werden.
            </param>
        <summary>
            Erstellungsvorgänge/Updates ein dienstnamespaces. Nach der Erstellung ist das ressourcenmanifest des Namespaces unveränderlich. Dieser Vorgang ist Idempotent.
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856303.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="parameters">
            Parameter, die zum Erstellen einer Ressource Namespace angegeben werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellungsvorgänge/Updates ein dienstnamespaces. Nach der Erstellung ist das ressourcenmanifest des Namespaces unveränderlich. Dieser Vorgang ist Idempotent.
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856303.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As SharedAccessAuthorizationRuleCreateOrUpdateParameters) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Aauthorization Regelname.
            </param>
        <param name="parameters">
            Die Autorisierungsregel für gemeinsamen Zugriff.
            </param>
        <summary>
            Erstellt eine Autorisierungsregel für einen namespace
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Aauthorization Regelname.
            </param>
        <param name="parameters">
            Die Autorisierungsregel für gemeinsamen Zugriff.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Autorisierungsregel für einen namespace
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Delete(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Delete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <summary>
            Löscht einen vorhandenen Namespace. Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen vorhandenen Namespace. Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Autorisierung Regelname.
            </param>
        <summary>
            Löscht eine Namespace-Autorisierungsregel
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Autorisierung Regelname.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Namespace-Autorisierungsregel
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Get (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Get(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Get(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Get (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <summary>
            Gibt die Beschreibung für den angegebenen Namespace zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; GetAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; GetAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt die Beschreibung für den angegebenen Namespace zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Name des Namespaces
            </param>
        <param name="authorizationRuleName">
            Autorisierung Regelname.
            </param>
        <summary>
            Ruft eine Autorisierungsregel für einen Namespace nach Name ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Name des Namespaces
            </param>
        <param name="authorizationRuleName">
            Autorisierung Regelname.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Autorisierungsregel für einen Namespace nach Name ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; List (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; List(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.List(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INamespacesOperations, resourceGroupName As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Wenn ResourceGroupName Wert null ist, führt die Methode alle Namespaces in Abonnement
            </param>
        <summary>
            Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAll (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAll(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAll(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INamespacesOperations) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAllAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAllNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAllNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAllNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Wenn ResourceGroupName Wert null ist, führt die Methode alle Namespaces in Abonnement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Name des Namespaces
            </param>
        <summary>
            Ruft die Autorisierungsregeln für einen Namespace.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Name des Namespaces
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Autorisierungsregeln für einen Namespace.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            Ruft die Autorisierungsregeln für einen Namespace.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            Ruft die Autorisierungsregeln für einen Namespace.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeys(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.
            </param>
        <summary>
            Ruft den primären und sekundären ConnectionStrings auf den namespace
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListKeysAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den primären und sekundären ConnectionStrings auf den namespace
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Patch (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Patch(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Patch(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As NamespacePatchParameters) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Patch (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="parameters">
            Um eine Ressource Namespace patch angegebenen Parametern.
            </param>
        <summary>
            Patches für den vorhandenen namespace
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; PatchAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; PatchAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.PatchAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.PatchAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;PatchAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="parameters">
            Um eine Ressource Namespace patch angegebenen Parametern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Patches für den vorhandenen namespace
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As PolicykeyResource) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.
            </param>
        <param name="parameters">
            Der Parameter angegeben, um den Namespace Autorisierung Regelschlüssel erneut generieren.
            </param>
        <summary>
            Generiert die primäre/sekundäre Schlüssel die Namespace-Autorisierungsregel
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="namespaceName">
            Der Namespacename.
            </param>
        <param name="authorizationRuleName">
            Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.
            </param>
        <param name="parameters">
            Der Parameter angegeben, um den Namespace Autorisierung Regelschlüssel erneut generieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Generiert die primäre/sekundäre Schlüssel die Namespace-Autorisierungsregel
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>