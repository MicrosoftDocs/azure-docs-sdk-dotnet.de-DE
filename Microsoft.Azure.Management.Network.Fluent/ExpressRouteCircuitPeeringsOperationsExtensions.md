<Type Name="ExpressRouteCircuitPeeringsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitPeeringsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitPeeringsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitPeeringsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitPeeringsOperationsExtensions = class" />
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
            Erweiterungsmethoden für ExpressRouteCircuitPeeringsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner peeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner peeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, peeringName, peeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="peeringParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="circuitName">
            Der Name der express-Route-Verbindung.
            </param>
        <param name="peeringName">
            Der Name von peering.
            </param>
        <param name="peeringParameters">
            Parameter zum Erstellen oder aktualisieren express Route Circuit peering Vorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein peering in der angegebenen express-Route-Verbindungen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="circuitName">
            Der Name der express-Route-Verbindung.
            </param>
        <param name="peeringName">
            Der Name von peering.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene peering mit der angegebenen express-Route-Verbindung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner peeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner peeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, peeringName, peeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="peeringParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="circuitName">
            Der Name der express-Route-Verbindung.
            </param>
        <param name="peeringName">
            Der Name von peering.
            </param>
        <param name="peeringParameters">
            Parameter zum Erstellen oder aktualisieren express Route Circuit peering Vorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein peering in der angegebenen express-Route-Verbindungen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="circuitName">
            Der Name der express-Route-Verbindung.
            </param>
        <param name="peeringName">
            Der Name von peering.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene peering mit der angegebenen express-Route-Verbindung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="circuitName">
            Der Name der express-Route-Verbindung.
            </param>
        <param name="peeringName">
            Der Name von peering.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Autorisierung aus der angegebenen express-Route-Verbindung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.ListAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="circuitName">
            Der Name der express-Route-Verbindung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle kann in einer angegebenen express-Route-Verbindung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitPeeringsOperations" RefType="this" />
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
            Ruft alle kann in einer angegebenen express-Route-Verbindung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>