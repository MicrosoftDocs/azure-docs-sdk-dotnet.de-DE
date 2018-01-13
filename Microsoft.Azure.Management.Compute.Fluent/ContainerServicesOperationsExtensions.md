<Type Name="ContainerServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ContainerServicesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="containerServiceName">
            Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.
            </param>
        <param name="parameters">
            Um das Erstellen oder Aktualisieren eines Container-Dienstvorgangs angegebenen Parameter.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen containerdienst.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt oder aktualisiert einen containerdienst mit der angegebenen Konfiguration von Orchestrator, Master und Agents.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="containerServiceName">
            Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den angegebenen Container-Dienst.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löscht den angegebenen Container-Dienst in der angegebenen Gruppe von Abonnement- und Ressourcenstatus. Der Vorgang löscht keine anderen Ressourcen, die als Teil des Erstellens eines Containers Diensts Speicherkonten, virtuelle Computer, einschließlich erstellt und Verfügbarkeitsgruppen. Alle anderen Ressourcen erstellt, mit dem containerdienst sind Teil der gleichen Ressourcengruppe und können einzeln gelöscht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="containerServiceName">
            Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.
            </param>
        <param name="parameters">
            Um das Erstellen oder Aktualisieren eines Container-Dienstvorgangs angegebenen Parameter.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen containerdienst.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt oder aktualisiert einen containerdienst mit der angegebenen Konfiguration von Orchestrator, Master und Agents.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="containerServiceName">
            Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den angegebenen Container-Dienst.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löscht den angegebenen Container-Dienst in der angegebenen Gruppe von Abonnement- und Ressourcenstatus. Der Vorgang löscht keine anderen Ressourcen, die als Teil des Erstellens eines Containers Diensts Speicherkonten, virtuelle Computer, einschließlich erstellt und Verfügbarkeitsgruppen. Alle anderen Ressourcen erstellt, mit dem containerdienst sind Teil der gleichen Ressourcengruppe und können einzeln gelöscht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.GetAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="containerServiceName">
            Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Eigenschaften des Diensts angegebenen Container ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die Eigenschaften des Diensts angegebenen Container in der angegebenen Abonnement und die Ressourcengruppe ab. Der Vorgang gibt die Eigenschaften, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und -Agents und FQDNs der Master-Shapes und Agents.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
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
            Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab. Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der Container-Dienste in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Container-Dienste in der angegebenen Gruppe von Abonnement- und Ressourcenstatus. Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
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
            Ruft eine Liste der Container-Dienste in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Container-Dienste in der angegebenen Gruppe von Abonnement- und Ressourcenstatus. Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
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
            Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab. Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>