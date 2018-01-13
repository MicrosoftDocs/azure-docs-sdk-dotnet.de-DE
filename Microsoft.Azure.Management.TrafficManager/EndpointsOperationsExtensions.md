<Type Name="EndpointsOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EndpointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EndpointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EndpointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EndpointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für EndpointsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Endpoint CreateOrUpdate (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Endpoint CreateOrUpdate(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String, parameters As Endpoint) As Endpoint" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, profileName, endpointType, endpointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, enthält die Traffic Manager-Endpunkt erstellt oder aktualisiert werden.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.
            </param>
        <param name="endpointName">
            Der Name des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.
            </param>
        <param name="parameters">
            Die Traffic Manager Endpunktparameter für den Vorgang CreateOrUpdate bereitgestellte.
            </param>
        <summary>
            Erstellt oder aktualisiert einen Traffic Manager-Endpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, enthält die Traffic Manager-Endpunkt erstellt oder aktualisiert werden.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.
            </param>
        <param name="endpointName">
            Der Name des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.
            </param>
        <param name="parameters">
            Die Traffic Manager Endpunktparameter für den Vorgang CreateOrUpdate bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen Traffic Manager-Endpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Delete(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String) As DeleteOperationResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Delete (operations, resourceGroupName, profileName, endpointType, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, gelöscht werden soll.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Traffic Manager-Endpunkt gelöscht werden soll.
            </param>
        <param name="endpointName">
            Der Name des Traffic Manager-Endpunkt gelöscht werden soll.
            </param>
        <summary>
            Löscht einen Traffic Manager-Endpunkt an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, gelöscht werden soll.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Traffic Manager-Endpunkt gelöscht werden soll.
            </param>
        <param name="endpointName">
            Der Name des Traffic Manager-Endpunkt gelöscht werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Traffic Manager-Endpunkt an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Endpoint Get (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Endpoint Get(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Get(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Get (operations, resourceGroupName, profileName, endpointType, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Traffic Manager-Endpunkt enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Traffic Manager-Endpunkt.
            </param>
        <param name="endpointName">
            Der Name des Traffic Manager-Endpunkt.
            </param>
        <summary>
            Ruft eine Traffic Manager-Endpunkt ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Traffic Manager-Endpunkt enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Traffic Manager-Endpunkt.
            </param>
        <param name="endpointName">
            Der Name des Traffic Manager-Endpunkt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Traffic Manager-Endpunkt ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Endpoint Update (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Endpoint Update(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Update(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String, parameters As Endpoint) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Update (operations, resourceGroupName, profileName, endpointType, endpointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, aktualisiert werden.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Endpunkts Traffic Manager aktualisiert werden.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts Traffic Manager aktualisiert werden.
            </param>
        <param name="parameters">
            Die Traffic Manager Endpunktparameter auf den Updatevorgang angegeben.
            </param>
        <summary>
            Aktualisieren Sie einen Traffic Manager-Endpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, aktualisiert werden.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="endpointType">
            Der Typ des Endpunkts Traffic Manager aktualisiert werden.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts Traffic Manager aktualisiert werden.
            </param>
        <param name="parameters">
            Die Traffic Manager Endpunktparameter auf den Updatevorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisieren Sie einen Traffic Manager-Endpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>