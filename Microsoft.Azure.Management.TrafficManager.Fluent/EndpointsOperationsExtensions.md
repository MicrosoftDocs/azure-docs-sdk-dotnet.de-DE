<Type Name="EndpointsOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EndpointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EndpointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EndpointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EndpointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
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
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointType">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
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
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;UpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
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