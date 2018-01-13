<Type Name="LocalNetworkGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LocalNetworkGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LocalNetworkGatewaysOperationsExtensions = class" />
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
            Erweiterungsmethoden für LocalNetworkGatewaysOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As LocalNetworkGateway) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.
            </param>
        <summary>
            Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDelete (operations, resourceGroupName, localNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <summary>
            Löscht das angegebene lokale Netzwerkgateway.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene lokale Netzwerkgateway.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginUpdateTags (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginUpdateTags(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As TagsObject) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.
            </param>
        <summary>
            Aktualisiert ein lokales Netzwerk-Gateway-Tags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
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
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein lokales Netzwerk-Gateway-Tags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway CreateOrUpdate (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway CreateOrUpdate(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As LocalNetworkGateway) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.
            </param>
        <summary>
            Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Delete(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Delete (operations, resourceGroupName, localNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <summary>
            Löscht das angegebene lokale Netzwerkgateway.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene lokale Netzwerkgateway.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway Get (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway Get(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Get (operations, resourceGroupName, localNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <summary>
            Ruft das angegebene lokale Netzwerkgateway in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; GetAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; GetAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft das angegebene lokale Netzwerkgateway in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; List (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; List(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.List(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String) As IPage(Of LocalNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
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
            Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
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
            Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; ListNext (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; ListNext(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILocalNetworkGatewaysOperations, nextPageLink As String) As IPage(Of LocalNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
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
            Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
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
            Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway UpdateTags (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway UpdateTags(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As TagsObject) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTags (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.
            </param>
        <summary>
            Aktualisiert ein lokales Netzwerk-Gateway-Tags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
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
        <param name="localNetworkGatewayName">
            Der Name des Gateways des lokalen Netzwerks.
            </param>
        <param name="parameters">
            Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein lokales Netzwerk-Gateway-Tags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>