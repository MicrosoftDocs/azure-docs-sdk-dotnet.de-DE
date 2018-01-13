<Type Name="VirtualNetworkGatewayConnectionsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewayConnectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewayConnectionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für VirtualNetworkGatewayConnectionsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Der Name des virtuellen Netzwerk-Gateway-Verbindung.
            </param>
        <param name="parameters">
            Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Der Name des virtuellen Netzwerk-Gateway-Verbindung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; BeginResetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int keyLength, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; BeginResetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int32 keyLength, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, keyLength, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginResetSharedKeyAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="keyLength" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.
            </param>
        <param name="keyLength">
            Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssellänge zurücksetzen, muss zwischen 1 und 128.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; BeginSetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; BeginSetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginSetSharedKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Der Name der virtuellen Netzwerk-Gateway-Verbindung.
            </param>
        <param name="value">
            Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssel-Wert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Der Name des virtuellen Netzwerk-Gateway-Verbindung.
            </param>
        <param name="parameters">
            Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Der Name des virtuellen Netzwerk-Gateway-Verbindung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Der Name des virtuellen Netzwerk-Gateway-Verbindung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene virtuelle Netzwerk-Gateway-Verbindung durch die Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; GetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; GetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetSharedKeyAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Die gatewayverbindung des virtuellen Netzwerks freigegeben Schlüsselnamen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der VirtualNetworkGatewayConnectionSharedKey Get-Vorgang ruft Informationen zu den angegebenen virtuellen Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel über dem netzwerkressourcenanbieter ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
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
            Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
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
            Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; ResetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int keyLength, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; ResetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int32 keyLength, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, keyLength, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ResetSharedKeyAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="keyLength" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.
            </param>
        <param name="keyLength">
            Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssellänge zurücksetzen, muss zwischen 1 und 128.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; SetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; SetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;SetSharedKeyAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            Der Name der virtuellen Netzwerk-Gateway-Verbindung.
            </param>
        <param name="value">
            Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssel-Wert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>