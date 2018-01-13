<Type Name="ProtectionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionPoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ProtectionPoliciesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource CreateOrUpdate (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource CreateOrUpdate(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IProtectionPoliciesOperations, vaultName As String, resourceGroupName As String, policyName As String, parameters As ProtectionPolicyResource) As ProtectionPolicyResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdate (operations, vaultName, resourceGroupName, policyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="policyName">
            Die Sicherungsrichtlinie erstellt werden soll.
            </param>
        <param name="parameters">
            Ressource Sicherungsrichtlinie
            </param>
        <summary>
            Erstellt oder ändert eine Sicherungsrichtlinie. Das ist ein asynchroner Vorgang.
            Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, vaultName, resourceGroupName, policyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="policyName">
            Die Sicherungsrichtlinie erstellt werden soll.
            </param>
        <param name="parameters">
            Ressource Sicherungsrichtlinie
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder ändert eine Sicherungsrichtlinie. Das ist ein asynchroner Vorgang.
            Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Delete(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IProtectionPoliciesOperations, vaultName As String, resourceGroupName As String, policyName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Delete (operations, vaultName, resourceGroupName, policyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="policyName">
            Die Sicherungsrichtlinie gelöscht werden soll.
            </param>
        <summary>
            Löscht den angegebenen Sicherungsrichtlinie aus Ihrer Recovery Services-Tresor. Das ist ein asynchroner Vorgang. Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.DeleteAsync (operations, vaultName, resourceGroupName, policyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="policyName">
            Die Sicherungsrichtlinie gelöscht werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den angegebenen Sicherungsrichtlinie aus Ihrer Recovery Services-Tresor. Das ist ein asynchroner Vorgang. Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionPoliciesOperations, vaultName As String, resourceGroupName As String, policyName As String) As ProtectionPolicyResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Get (operations, vaultName, resourceGroupName, policyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="policyName">
            Sicherungsrichtlinie Informationen abgerufen werden sollen.
            </param>
        <summary>
            Enthält die Details der Sicherungsrichtlinien, die Recovery Services-Tresor zugeordnet sind. Das ist ein asynchroner Vorgang. Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, policyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="policyName">
            Sicherungsrichtlinie Informationen abgerufen werden sollen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Enthält die Details der Sicherungsrichtlinien, die Recovery Services-Tresor zugeordnet sind. Das ist ein asynchroner Vorgang. Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>