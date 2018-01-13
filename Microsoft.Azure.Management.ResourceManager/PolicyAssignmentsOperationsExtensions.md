<Type Name="PolicyAssignmentsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PolicyAssignmentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PolicyAssignmentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PolicyAssignmentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PolicyAssignmentsOperationsExtensions = class" />
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
            Erweiterungsmethoden für PolicyAssignmentsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Create (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Create(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Create(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IPolicyAssignmentsOperations, scope As String, policyAssignmentName As String, parameters As PolicyAssignment) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Create (operations, scope, policyAssignmentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der für richtlinienzuweisung.
            </param>
        <param name="policyAssignmentName">
            Der Name der richtlinienzuweisung.
            </param>
        <param name="parameters">
            Parameter für die Zuweisung der Konfigurationsrichtlinie.
            </param>
        <summary>
            Erstellt eine Zuweisung der Konfigurationsrichtlinie.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt. Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateAsync (operations, scope, policyAssignmentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der für richtlinienzuweisung.
            </param>
        <param name="policyAssignmentName">
            Der Name der richtlinienzuweisung.
            </param>
        <param name="parameters">
            Parameter für die Zuweisung der Konfigurationsrichtlinie.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Zuweisung der Konfigurationsrichtlinie.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt. Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment CreateById (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment CreateById(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateById(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateById (operations As IPolicyAssignmentsOperations, policyAssignmentId As String, parameters As PolicyAssignment) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member CreateById : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateById (operations, policyAssignmentId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="policyAssignmentId">
            Die ID der für richtlinienzuweisung zu erstellen. Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".
            </param>
        <param name="parameters">
            Parameter für die Zuweisung der Konfigurationsrichtlinie.
            </param>
        <summary>
            Erstellt eine richtlinienzuweisung anhand der ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt. Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird. Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateByIdAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateByIdAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateByIdAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateByIdAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateByIdAsync (operations, policyAssignmentId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;CreateByIdAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="policyAssignmentId">
            Die ID der für richtlinienzuweisung zu erstellen. Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".
            </param>
        <param name="parameters">
            Parameter für die Zuweisung der Konfigurationsrichtlinie.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine richtlinienzuweisung anhand der ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt. Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird. Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Delete (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Delete(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IPolicyAssignmentsOperations, scope As String, policyAssignmentName As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Delete (operations, scope, policyAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der für richtlinienzuweisung.
            </param>
        <param name="policyAssignmentName">
            Der Name der richtlinienzuweisung zu löschen.
            </param>
        <summary>
            Löscht eine richtlinienzuweisung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteAsync (operations, scope, policyAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der für richtlinienzuweisung.
            </param>
        <param name="policyAssignmentName">
            Der Name der richtlinienzuweisung zu löschen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine richtlinienzuweisung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment DeleteById (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment DeleteById(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteById(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteById (operations As IPolicyAssignmentsOperations, policyAssignmentId As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member DeleteById : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteById (operations, policyAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="policyAssignmentId">
            Die ID der für richtlinienzuweisung zu löschen. Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".
            </param>
        <summary>
            Löscht eine richtlinienzuweisung anhand der ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteByIdAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteByIdAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteByIdAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteByIdAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteByIdAsync (operations, policyAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;DeleteByIdAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="policyAssignmentId">
            Die ID der für richtlinienzuweisung zu löschen. Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine richtlinienzuweisung anhand der ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Get (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Get(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPolicyAssignmentsOperations, scope As String, policyAssignmentName As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Get (operations, scope, policyAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der für richtlinienzuweisung.
            </param>
        <param name="policyAssignmentName">
            Der Name der richtlinienzuweisung abgerufen.
            </param>
        <summary>
            Ruft eine richtlinienzuweisung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetAsync (operations, scope, policyAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der für richtlinienzuweisung.
            </param>
        <param name="policyAssignmentName">
            Der Name der richtlinienzuweisung abgerufen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine richtlinienzuweisung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment GetById (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment GetById(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetById(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetById (operations As IPolicyAssignmentsOperations, policyAssignmentId As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member GetById : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetById (operations, policyAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="policyAssignmentId">
            Die ID der richtlinienzuweisung abgerufen werden soll. Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".
            </param>
        <summary>
            Ruft eine richtlinienzuweisung anhand der ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetByIdAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetByIdAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetByIdAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByIdAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetByIdAsync (operations, policyAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;GetByIdAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="policyAssignmentId">
            Die ID der richtlinienzuweisung abgerufen werden soll. Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine richtlinienzuweisung anhand der ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; List (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; List(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPolicyAssignmentsOperations, Optional odataQuery As ODataQuery(Of PolicyAssignment) = null) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <summary>
            Ruft die richtlinienzuweisungen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
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
            Ruft die richtlinienzuweisungen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResource">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResource (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResource(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResource(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResource (operations As IPolicyAssignmentsOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, Optional odataQuery As ODataQuery(Of PolicyAssignment) = null) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResource : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResource (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters.
            </param>
        <param name="parentResourcePath">
            Die übergeordnete Ressourcenpfad.
            </param>
        <param name="resourceType">
            Der Ressourcentyp.
            </param>
        <param name="resourceName">
            Der Name der Ressource mit zugewiesenen Richtlinien.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <summary>
            Ruft die richtlinienzuweisungen für eine Ressource ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters.
            </param>
        <param name="parentResourcePath">
            Die übergeordnete Ressourcenpfad.
            </param>
        <param name="resourceType">
            Der Ressourcentyp.
            </param>
        <param name="resourceName">
            Der Name der Ressource mit zugewiesenen Richtlinien.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die richtlinienzuweisungen für eine Ressource ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroup (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroup(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroup(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroup (operations As IPolicyAssignmentsOperations, resourceGroupName As String, Optional filter As String = null) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroup : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroup (operations, resourceGroupName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die richtlinienzuweisungen enthält.
            </param>
        <param name="filter">
            Der Filter auf die Operation angewendet werden soll.
            </param>
        <summary>
            Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupAsync (operations, resourceGroupName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die richtlinienzuweisungen enthält.
            </param>
        <param name="filter">
            Der Filter auf die Operation angewendet werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroupNext (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroupNext(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNext(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroupNext (operations As IPolicyAssignmentsOperations, nextPageLink As String) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupNext : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
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
            Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceGroupNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
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
            Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceNext (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceNext(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNext(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceNext (operations As IPolicyAssignmentsOperations, nextPageLink As String) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResourceNext : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
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
            Ruft die richtlinienzuweisungen für eine Ressource ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
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
            Ruft die richtlinienzuweisungen für eine Ressource ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPolicyAssignmentsOperations, nextPageLink As String) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
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
            Ruft die richtlinienzuweisungen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
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
            Ruft die richtlinienzuweisungen für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>