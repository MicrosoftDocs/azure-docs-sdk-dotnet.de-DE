<Type Name="DeploymentsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeploymentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeploymentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeploymentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeploymentsOperationsExtensions = class" />
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
            Erweiterungsmethoden für DeploymentsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended BeginCreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended BeginCreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String, parameters As Deployment) As DeploymentExtended" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, deploymentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe an die Ressourcen bereitstellen. Der Name wird Groß-/Kleinschreibung nicht beachtet. Die Ressourcengruppe muss bereits vorhanden sein.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung
            </param>
        <param name="parameters">
            Zusätzliche Parameter für den Vorgang bereitgestellte.
            </param>
        <summary>
            Stellt Ressourcen in einer Ressourcengruppe bereit.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können die Vorlage und die Parameter direkt in der Anforderung oder den Link, um JSON-Dateien bereitstellen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe an die Ressourcen bereitstellen. Der Name wird Groß-/Kleinschreibung nicht beachtet. Die Ressourcengruppe muss bereits vorhanden sein.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung
            </param>
        <param name="parameters">
            Zusätzliche Parameter für den Vorgang bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt Ressourcen in einer Ressourcengruppe bereit.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können die Vorlage und die Parameter direkt in der Anforderung oder den Link, um JSON-Dateien bereitstellen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginDelete (operations, resourceGroupName, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe mit der Bereitstellung gelöscht. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung gelöscht.
            </param>
        <summary>
            Löscht eine Bereitstellung aus dem Bereitstellungsverlauf an.
            </summary>
        <remarks>
            Eine vorlagenbereitstellung, die zurzeit ausgeführt wird, kann nicht gelöscht werden. Das Löschen einer vorlagenbereitstellung werden die zugehörigen Bereitstellungsvorgänge entfernt.
            Das Löschen einer vorlagenbereitstellung wirkt sich nicht auf den Status der Ressourcengruppe aus. Dies ist ein asynchroner Vorgang, der den Status 202 zurückgibt, bis die vorlagenbereitstellung erfolgreich gelöscht wurde. Antwortheaders der Adresse enthält den URI, der verwendet wird, um den Status des Prozesses zu erhalten.
            Während der Prozess ausgeführt wird, gibt ein Aufruf des URIS im Location-Header den Status 202 zurück. Wenn der Prozess abgeschlossen wurde, gibt der URI im Location-Header Status 204 bei Erfolg zurück. Wenn die asynchrone Anforderung fehlgeschlagen ist, gibt der URI im Location-Header einen Fehlerstufen-Statuscode zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe mit der Bereitstellung gelöscht. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung gelöscht.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Bereitstellung aus dem Bereitstellungsverlauf an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Eine vorlagenbereitstellung, die zurzeit ausgeführt wird, kann nicht gelöscht werden. Das Löschen einer vorlagenbereitstellung werden die zugehörigen Bereitstellungsvorgänge entfernt.
            Das Löschen einer vorlagenbereitstellung wirkt sich nicht auf den Status der Ressourcengruppe aus. Dies ist ein asynchroner Vorgang, der den Status 202 zurückgibt, bis die vorlagenbereitstellung erfolgreich gelöscht wurde. Antwortheaders der Adresse enthält den URI, der verwendet wird, um den Status des Prozesses zu erhalten.
            Während der Prozess ausgeführt wird, gibt ein Aufruf des URIS im Location-Header den Status 202 zurück. Wenn der Prozess abgeschlossen wurde, gibt der URI im Location-Header Status 204 bei Erfolg zurück. Wenn die asynchrone Anforderung fehlgeschlagen ist, gibt der URI im Location-Header einen Fehlerstufen-Statuscode zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public static void Cancel (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Cancel(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Cancel(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Cancel (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String)" />
      <MemberSignature Language="F#" Value="static member Cancel : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Cancel (operations, resourceGroupName, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung auf "Abbrechen".
            </param>
        <summary>
            Bricht einen derzeit ausgeführten vorlagenbereitstellung ab.
            </summary>
        <remarks>
            Sie können eine Bereitstellung "Abbrechen", nur dann, wenn der ProvisioningState akzeptiert oder ausgeführt wird. Nachdem die Bereitstellung abgebrochen wird, wird der ProvisioningState auf Canceled festgelegt. Abbrechen einer vorlagenbereitstellung wird die aktuell ausgeführte vorlagenbereitstellung beendet und verlässt Ressourcengruppe teilweise bereitgestellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CancelAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CancelAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;CancelAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung auf "Abbrechen".
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Bricht einen derzeit ausgeführten vorlagenbereitstellung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können eine Bereitstellung "Abbrechen", nur dann, wenn der ProvisioningState akzeptiert oder ausgeführt wird. Nachdem die Bereitstellung abgebrochen wird, wird der ProvisioningState auf Canceled festgelegt. Abbrechen einer vorlagenbereitstellung wird die aktuell ausgeführte vorlagenbereitstellung beendet und verlässt Ressourcengruppe teilweise bereitgestellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistence">
      <MemberSignature Language="C#" Value="public static bool CheckExistence (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistence(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CheckExistence(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistence (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistence : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CheckExistence (operations, resourceGroupName, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der mit der Bereitstellung zu überprüfenden Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung zu überprüfen.
            </param>
        <summary>
            Überprüft, ob die Bereitstellung vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der mit der Bereitstellung zu überprüfenden Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung zu überprüfen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob die Bereitstellung vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String, parameters As Deployment) As DeploymentExtended" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, deploymentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe an die Ressourcen bereitstellen. Der Name wird Groß-/Kleinschreibung nicht beachtet. Die Ressourcengruppe muss bereits vorhanden sein.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung
            </param>
        <param name="parameters">
            Zusätzliche Parameter für den Vorgang bereitgestellte.
            </param>
        <summary>
            Stellt Ressourcen in einer Ressourcengruppe bereit.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können die Vorlage und die Parameter direkt in der Anforderung oder den Link, um JSON-Dateien bereitstellen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe an die Ressourcen bereitstellen. Der Name wird Groß-/Kleinschreibung nicht beachtet. Die Ressourcengruppe muss bereits vorhanden sein.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung
            </param>
        <param name="parameters">
            Zusätzliche Parameter für den Vorgang bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt Ressourcen in einer Ressourcengruppe bereit.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können die Vorlage und die Parameter direkt in der Anforderung oder den Link, um JSON-Dateien bereitstellen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Delete (operations, resourceGroupName, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe mit der Bereitstellung gelöscht. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung gelöscht.
            </param>
        <summary>
            Löscht eine Bereitstellung aus dem Bereitstellungsverlauf an.
            </summary>
        <remarks>
            Eine vorlagenbereitstellung, die zurzeit ausgeführt wird, kann nicht gelöscht werden. Das Löschen einer vorlagenbereitstellung werden die zugehörigen Bereitstellungsvorgänge entfernt.
            Das Löschen einer vorlagenbereitstellung wirkt sich nicht auf den Status der Ressourcengruppe aus. Dies ist ein asynchroner Vorgang, der den Status 202 zurückgibt, bis die vorlagenbereitstellung erfolgreich gelöscht wurde. Antwortheaders der Adresse enthält den URI, der verwendet wird, um den Status des Prozesses zu erhalten.
            Während der Prozess ausgeführt wird, gibt ein Aufruf des URIS im Location-Header den Status 202 zurück. Wenn der Prozess abgeschlossen wurde, gibt der URI im Location-Header Status 204 bei Erfolg zurück. Wenn die asynchrone Anforderung fehlgeschlagen ist, gibt der URI im Location-Header einen Fehlerstufen-Statuscode zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe mit der Bereitstellung gelöscht. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung gelöscht.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Bereitstellung aus dem Bereitstellungsverlauf an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Eine vorlagenbereitstellung, die zurzeit ausgeführt wird, kann nicht gelöscht werden. Das Löschen einer vorlagenbereitstellung werden die zugehörigen Bereitstellungsvorgänge entfernt.
            Das Löschen einer vorlagenbereitstellung wirkt sich nicht auf den Status der Ressourcengruppe aus. Dies ist ein asynchroner Vorgang, der den Status 202 zurückgibt, bis die vorlagenbereitstellung erfolgreich gelöscht wurde. Antwortheaders der Adresse enthält den URI, der verwendet wird, um den Status des Prozesses zu erhalten.
            Während der Prozess ausgeführt wird, gibt ein Aufruf des URIS im Location-Header den Status 202 zurück. Wenn der Prozess abgeschlossen wurde, gibt der URI im Location-Header Status 204 bei Erfolg zurück. Wenn die asynchrone Anforderung fehlgeschlagen ist, gibt der URI im Location-Header einen Fehlerstufen-Statuscode zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult ExportTemplate (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult ExportTemplate(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ExportTemplate(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportTemplate (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String) As DeploymentExportResult" />
      <MemberSignature Language="F#" Value="static member ExportTemplate : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ExportTemplate (operations, resourceGroupName, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung von dem die Vorlage abgerufen werden soll.
            </param>
        <summary>
            Exportiert die Vorlage für eine angegebene Bereitstellung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung von dem die Vorlage abgerufen werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Exportiert die Vorlage für eine angegebene Bereitstellung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended Get (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended Get(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String) As DeploymentExtended" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Get (operations, resourceGroupName, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung abgerufen werden soll.
            </param>
        <summary>
            Ruft eine Bereitstellung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.GetAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung abgerufen werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Bereitstellung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; ListByResourceGroup (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; ListByResourceGroup(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IDeploymentsOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of DeploymentExtendedFilter) = null) As IPage(Of DeploymentExtended)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe mit dem Bereitstellungen abgerufen werden soll. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <summary>
            Rufen Sie alle Bereitstellungen für eine Ressourcengruppe ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe mit dem Bereitstellungen abgerufen werden soll. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie alle Bereitstellungen für eine Ressourcengruppe ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IDeploymentsOperations, nextPageLink As String) As IPage(Of DeploymentExtended)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
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
            Rufen Sie alle Bereitstellungen für eine Ressourcengruppe ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
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
            Rufen Sie alle Bereitstellungen für eine Ressourcengruppe ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult Validate (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult Validate(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Validate(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Validate (operations As IDeploymentsOperations, resourceGroupName As String, deploymentName As String, parameters As Deployment) As DeploymentValidateResult" />
      <MemberSignature Language="F#" Value="static member Validate : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.Validate (operations, resourceGroupName, deploymentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe wird in die Vorlage bereitgestellt werden. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung
            </param>
        <param name="parameters">
            Parameter, um zu überprüfen.
            </param>
        <summary>
            Überprüft, ob die angegebene Vorlage syntaktisch richtig ist und werden von Azure Resource Manager akzeptiert...
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt; ValidateAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt; ValidateAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ValidateAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions.ValidateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentsOperationsExtensions/&lt;ValidateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe wird in die Vorlage bereitgestellt werden. Der Name wird Groß-/Kleinschreibung nicht beachtet.
            </param>
        <param name="deploymentName">
            Der Name der Bereitstellung
            </param>
        <param name="parameters">
            Parameter, um zu überprüfen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob die angegebene Vorlage syntaktisch richtig ist und werden von Azure Resource Manager akzeptiert...
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>