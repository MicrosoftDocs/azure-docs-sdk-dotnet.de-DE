<Type Name="NetworkWatchersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkWatchersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkWatchersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für NetworkWatchersOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectivityInformation BeginCheckConnectivity (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectivityInformation BeginCheckConnectivity(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivity(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCheckConnectivity (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As ConnectivityParameters) As ConnectivityInformation" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivity : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivity (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivityInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.
            </param>
        <summary>
            Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; BeginCheckConnectivityAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; BeginCheckConnectivityAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivityAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginCheckConnectivityAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDelete (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <summary>
            Löscht die angegebene Netzwerk-Watcher-Ressource.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Netzwerk-Watcher-Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AzureReachabilityReport BeginGetAzureReachabilityReport (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport BeginGetAzureReachabilityReport(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReport(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetAzureReachabilityReport (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AzureReachabilityReportParameters) As AzureReachabilityReport" />
      <MemberSignature Language="F#" Value="static member BeginGetAzureReachabilityReport : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReport (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.
            </param>
        <summary>
            Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; BeginGetAzureReachabilityReportAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; BeginGetAzureReachabilityReportAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReportAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetAzureReachabilityReportAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReportAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetAzureReachabilityReportAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginGetFlowLogStatus (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginGetFlowLogStatus(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatus(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetFlowLogStatus (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogStatusParameters) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatus : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatus (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.
            </param>
        <summary>
            Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginGetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginGetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatusAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetFlowLogStatusAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NextHopResult BeginGetNextHop (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NextHopResult BeginGetNextHop(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHop(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetNextHop (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NextHopParameters) As NextHopResult" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHop : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters -&gt; Microsoft.Azure.Management.Network.Models.NextHopResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHop (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NextHopResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Quelle und Ziel-Endpunkt zu definieren.
            </param>
        <summary>
            Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt; BeginGetNextHopAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt; BeginGetNextHopAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHopAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetNextHopAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Quelle und Ziel-Endpunkt zu definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshooting">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshooting (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshooting(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshooting(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetTroubleshooting (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshooting : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshooting (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Ressource zur Problembehandlung bei definieren.
            </param>
        <summary>
            Initiieren Sie die Problembehandlung wird für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Ressource zur Problembehandlung bei definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Initiieren Sie die Problembehandlung wird für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResult">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshootingResult (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshootingResult(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResult(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetTroubleshootingResult (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As QueryTroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResult : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResult (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.
            </param>
        <summary>
            Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingResultAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult BeginGetVMSecurityRules (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult BeginGetVMSecurityRules(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRules(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetVMSecurityRules (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As SecurityGroupViewParameters) As SecurityGroupViewResult" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRules : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRules (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.
            </param>
        <summary>
            Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; BeginGetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; BeginGetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetVMSecurityRulesAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProviders">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AvailableProvidersList BeginListAvailableProviders (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AvailableProvidersList BeginListAvailableProviders(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProviders(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListAvailableProviders (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AvailableProvidersListParameters) As AvailableProvidersList" />
      <MemberSignature Language="F#" Value="static member BeginListAvailableProviders : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersList" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProviders (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AvailableProvidersList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Liste der verfügbaren Anbieter Bereich.
            </param>
        <summary>
            Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProvidersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; BeginListAvailableProvidersAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; BeginListAvailableProvidersAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProvidersAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListAvailableProvidersAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProvidersAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginListAvailableProvidersAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Liste der verfügbaren Anbieter Bereich.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginSetFlowLogConfiguration (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginSetFlowLogConfiguration(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfiguration(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginSetFlowLogConfiguration (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogInformation) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfiguration : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfiguration (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.
            </param>
        <summary>
            Konfiguriert Flow-Protokoll für eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginSetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginSetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginSetFlowLogConfigurationAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Konfiguriert Flow-Protokoll für eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlow">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult BeginVerifyIPFlow (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult BeginVerifyIPFlow(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlow(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginVerifyIPFlow (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As VerificationIPFlowParameters) As VerificationIPFlowResult" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlow : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlow (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.
            </param>
        <summary>
            Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; BeginVerifyIPFlowAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; BeginVerifyIPFlowAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlowAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginVerifyIPFlowAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectivityInformation CheckConnectivity (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectivityInformation CheckConnectivity(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivity(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckConnectivity (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As ConnectivityParameters) As ConnectivityInformation" />
      <MemberSignature Language="F#" Value="static member CheckConnectivity : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivity (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivityInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.
            </param>
        <summary>
            Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; CheckConnectivityAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; CheckConnectivityAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivityAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckConnectivityAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;CheckConnectivityAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher CreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher CreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NetworkWatcher) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Watcher-Netzwerkressource definieren.
            </param>
        <summary>
            Erstellt oder aktualisiert eine netzwerküberwachung in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Watcher-Netzwerkressource definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine netzwerküberwachung in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Delete(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Delete (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <summary>
            Löscht die angegebene Netzwerk-Watcher-Ressource.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Netzwerk-Watcher-Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher Get (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher Get(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Get (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <summary>
            Ruft die angegebene Netzwerk-Watcher durch Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Netzwerk-Watcher durch Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AzureReachabilityReport GetAzureReachabilityReport (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport GetAzureReachabilityReport(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReport(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAzureReachabilityReport (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AzureReachabilityReportParameters) As AzureReachabilityReport" />
      <MemberSignature Language="F#" Value="static member GetAzureReachabilityReport : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReport (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.
            </param>
        <summary>
            Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; GetAzureReachabilityReportAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; GetAzureReachabilityReportAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReportAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAzureReachabilityReportAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReportAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetAzureReachabilityReportAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation GetFlowLogStatus (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation GetFlowLogStatus(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatus(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFlowLogStatus (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogStatusParameters) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatus : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatus (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.
            </param>
        <summary>
            Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; GetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; GetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatusAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetFlowLogStatusAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NextHopResult GetNextHop (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NextHopResult GetNextHop(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHop(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetNextHop (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NextHopParameters) As NextHopResult" />
      <MemberSignature Language="F#" Value="static member GetNextHop : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters -&gt; Microsoft.Azure.Management.Network.Models.NextHopResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHop (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NextHopResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Quelle und Ziel-Endpunkt zu definieren.
            </param>
        <summary>
            Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt; GetNextHopAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt; GetNextHopAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHopAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNextHopAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetNextHopAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Quelle und Ziel-Endpunkt zu definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopology">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Topology GetTopology (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Topology GetTopology(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopology(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTopology (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TopologyParameters) As Topology" />
      <MemberSignature Language="F#" Value="static member GetTopology : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters -&gt; Microsoft.Azure.Management.Network.Models.Topology" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopology (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Topology</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Darstellung von Topologie zu definieren.
            </param>
        <summary>
            Ruft die aktuelle Netzwerktopologie von Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt; GetTopologyAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Topology&gt; GetTopologyAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopologyAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTopologyAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopologyAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTopologyAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die die Darstellung von Topologie zu definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die aktuelle Netzwerktopologie von Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshooting">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshooting (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshooting(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshooting(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTroubleshooting (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member GetTroubleshooting : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshooting (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Ressource zur Problembehandlung bei definieren.
            </param>
        <summary>
            Initiieren Sie die Problembehandlung wird für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Ressource zur Problembehandlung bei definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Initiieren Sie die Problembehandlung wird für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResult">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshootingResult (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshootingResult(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResult(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTroubleshootingResult (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As QueryTroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResult : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResult (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.
            </param>
        <summary>
            Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingResultAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult GetVMSecurityRules (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult GetVMSecurityRules(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRules(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVMSecurityRules (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As SecurityGroupViewParameters) As SecurityGroupViewResult" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRules : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRules (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.
            </param>
        <summary>
            Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; GetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; GetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetVMSecurityRulesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; List (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; List(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkWatchersOperations, resourceGroupName As String) As IEnumerable(Of NetworkWatcher)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <summary>
            Ruft alle Netzwerk-Watcher durch Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; ListAll (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; ListAll(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.INetworkWatchersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INetworkWatchersOperations) As IEnumerable(Of NetworkWatcher)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.INetworkWatchersOperations -&gt; seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Ruft alle Netzwerk-Watcher nach Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAllAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
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
            Ruft alle Netzwerk-Watcher nach Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
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
            Ruft alle Netzwerk-Watcher durch Ressourcengruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProviders">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AvailableProvidersList ListAvailableProviders (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AvailableProvidersList ListAvailableProviders(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProviders(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableProviders (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AvailableProvidersListParameters) As AvailableProvidersList" />
      <MemberSignature Language="F#" Value="static member ListAvailableProviders : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersList" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProviders (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AvailableProvidersList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Liste der verfügbaren Anbieter Bereich.
            </param>
        <summary>
            Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProvidersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; ListAvailableProvidersAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; ListAvailableProvidersAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProvidersAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableProvidersAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProvidersAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAvailableProvidersAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Liste der verfügbaren Anbieter Bereich.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation SetFlowLogConfiguration (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation SetFlowLogConfiguration(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfiguration(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetFlowLogConfiguration (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogInformation) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfiguration : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfiguration (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.
            </param>
        <summary>
            Konfiguriert Flow-Protokoll für eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; SetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; SetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;SetFlowLogConfigurationAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, Netzwerk-Watcher.
            </param>
        <param name="networkWatcherName">
            Der Name der Watcher Netzwerkressource.
            </param>
        <param name="parameters">
            Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Konfiguriert Flow-Protokoll für eine angegebene Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher UpdateTags (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher UpdateTags(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TagsObject) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTags (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Der Parameter angegeben wird, um die Netzwerk-Watcher-Tags zu aktualisieren.
            </param>
        <summary>
            Aktualisiert eine Netzwerk-Watcher-Tags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Der Parameter angegeben wird, um die Netzwerk-Watcher-Tags zu aktualisieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine Netzwerk-Watcher-Tags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlow">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult VerifyIPFlow (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult VerifyIPFlow(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlow(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function VerifyIPFlow (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As VerificationIPFlowParameters) As VerificationIPFlowResult" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlow : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlow (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.
            </param>
        <summary>
            Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; VerifyIPFlowAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; VerifyIPFlowAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlowAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;VerifyIPFlowAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="networkWatcherName">
            Der Name des Netzwerk-Watcher.
            </param>
        <param name="parameters">
            Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>