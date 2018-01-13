<Type Name="VirtualNetworkPeeringsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkPeeringsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkPeeringsOperationsExtensions = class" />
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
            Erweiterungsmethoden für VirtualNetworkPeeringsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkName">
            Der Name des virtuellen Netzwerks.
            </param>
        <param name="virtualNetworkPeeringName">
            Der Name von peering.
            </param>
        <param name="virtualNetworkPeeringParameters">
            Parameter zum Erstellen oder aktualisieren virtuelles Netzwerk peering Vorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein peering im angegebenen virtuellen Netzwerk.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkName">
            Der Name des virtuellen Netzwerks.
            </param>
        <param name="virtualNetworkPeeringName">
            Der Name des virtuellen Netzwerks peering.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene virtuelle Netzwerk-peering.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkName">
            Der Name des virtuellen Netzwerks.
            </param>
        <param name="virtualNetworkPeeringName">
            Der Name von peering.
            </param>
        <param name="virtualNetworkPeeringParameters">
            Parameter zum Erstellen oder aktualisieren virtuelles Netzwerk peering Vorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein peering im angegebenen virtuellen Netzwerk.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkName">
            Der Name des virtuellen Netzwerks.
            </param>
        <param name="virtualNetworkPeeringName">
            Der Name des virtuellen Netzwerks peering.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene virtuelle Netzwerk-peering.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkName">
            Der Name des virtuellen Netzwerks.
            </param>
        <param name="virtualNetworkPeeringName">
            Der Name des virtuellen Netzwerks peering.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft das angegebene virtuelle Netzwerk-peering.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualNetworkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="virtualNetworkName">
            Der Name des virtuellen Netzwerks.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle virtuellen Netzwerk über Peerings in einem virtuellen Netzwerk an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
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
            Ruft alle virtuellen Netzwerk über Peerings in einem virtuellen Netzwerk an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>