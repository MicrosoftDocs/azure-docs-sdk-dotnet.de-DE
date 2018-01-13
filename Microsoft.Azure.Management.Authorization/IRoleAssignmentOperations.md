<Type Name="IRoleAssignmentOperations" FullName="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations">
  <TypeSignature Language="C#" Value="public interface IRoleAssignmentOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRoleAssignmentOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRoleAssignmentOperations" />
  <TypeSignature Language="F#" Value="type IRoleAssignmentOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            TBD (http://TBD für Weitere Informationen siehe)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateAsync (string scope, Guid roleAssignmentName, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateAsync(string scope, valuetype System.Guid roleAssignmentName, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.CreateAsync(System.String,System.Guid,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * Guid * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;" Usage="iRoleAssignmentOperations.CreateAsync (scope, roleAssignmentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            Bereich.
            </param>
        <param name="roleAssignmentName">
            Name der Rolle Zuweisung.
            </param>
        <param name="parameters">
            Rollenzuweisung.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Rollenzuweisung zu erstellen.
            </summary>
        <returns>
            Zuweisungen Erstellung-rollenergebnissen
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateByIdAsync (string roleAssignmentId, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateByIdAsync(string roleAssignmentId, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.CreateByIdAsync(System.String,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateByIdAsync : string * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;" Usage="iRoleAssignmentOperations.CreateByIdAsync (roleAssignmentId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleAssignmentId">
            Rollenzuweisung Id
            </param>
        <param name="parameters">
            Rollenzuweisung.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie die rollenzuweisung nach ID auf.
            </summary>
        <returns>
            Zuweisungen Erstellung-rollenergebnissen
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteAsync (string scope, Guid roleAssignmentName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteAsync(string scope, valuetype System.Guid roleAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.DeleteAsync(System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;" Usage="iRoleAssignmentOperations.DeleteAsync (scope, roleAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            Bereich.
            </param>
        <param name="roleAssignmentName">
            Name der Rolle Zuweisung.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Löschen Sie rollenzuweisung.
            </summary>
        <returns>
            Löschen von rollenzuweisungen Ergebnis
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteByIdAsync (string roleAssignmentId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteByIdAsync(string roleAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.DeleteByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;" Usage="iRoleAssignmentOperations.DeleteByIdAsync (roleAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleAssignmentId">
            Rollenzuweisung Id
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Löschen Sie rollenzuweisung.
            </summary>
        <returns>
            Löschen von rollenzuweisungen Ergebnis
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetAsync (string scope, Guid roleAssignmentName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetAsync(string scope, valuetype System.Guid roleAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.GetAsync(System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;" Usage="iRoleAssignmentOperations.GetAsync (scope, roleAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            Bereich.
            </param>
        <param name="roleAssignmentName">
            Name der Rolle Zuweisung.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Rufen Sie einzelne rollenzuweisung.
            </summary>
        <returns>
            Rollenzuweisung vorgangsergebnis zu erhalten.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetByIdAsync (string roleAssignmentId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetByIdAsync(string roleAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.GetByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;" Usage="iRoleAssignmentOperations.GetByIdAsync (roleAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleAssignmentId">
            Rollenzuweisung Id
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Rufen Sie einzelne rollenzuweisung.
            </summary>
        <returns>
            Rollenzuweisung vorgangsergebnis zu erhalten.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListAsync (Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListAsync(class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListAsync(Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            Vorgang filtert. Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen des Abonnements ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceAsync (string resourceGroupName, Microsoft.Azure.ResourceIdentity identity, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceAsync(string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceAsync(System.String,Microsoft.Azure.ResourceIdentity,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceAsync : string * Microsoft.Azure.ResourceIdentity * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceAsync (resourceGroupName, identity, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="identity">
            Identität der Ressource.
            </param>
        <param name="parameters">
            Vorgang filtert. Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressource zurück.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen der Ressource ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupAsync (string resourceGroupName, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupAsync(string resourceGroupName, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceGroupAsync(System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupAsync : string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceGroupAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Name der Ressourcengruppe.
            </param>
        <param name="parameters">
            Vorgang filtert. Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressourcengruppe zurück.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen der Ressourcengruppe ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceGroupNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceGroupNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen der Ressourcengruppe ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen der Ressource ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScopeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeAsync (string scope, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeAsync(string scope, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForScopeAsync(System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForScopeAsync : string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForScopeAsync (scope, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            Bereich.
            </param>
        <param name="parameters">
            Vorgang filtert. Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen des Bereichs ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScopeNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForScopeNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForScopeNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForScopeNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen des Bereichs ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die rollenzuweisungen des Abonnements ab.
            </summary>
        <returns>
            Rolle Zuweisung Liste vorgangsergebnis.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>