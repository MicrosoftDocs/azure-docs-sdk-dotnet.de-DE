<Type Name="ExpressRouteCircuitAuthorizationsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitAuthorizationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitAuthorizationsOperationsExtensions = class" />
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
            Erweiterungsmethoden für ExpressRouteCircuitAuthorizationsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" />
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
        <param name="authorizationName">
            Der Name der Autorisierung.
            </param>
        <param name="authorizationParameters">
            Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
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
        <param name="authorizationName">
            Der Name der Autorisierung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" />
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
        <param name="authorizationName">
            Der Name der Autorisierung.
            </param>
        <param name="authorizationParameters">
            Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
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
        <param name="authorizationName">
            Der Name der Autorisierung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
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
        <param name="authorizationName">
            Der Name der Autorisierung.
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
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
            Der Name der Verbindung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle autorisierungen in einer express-Route-Verbindung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
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
            Ruft alle autorisierungen in einer express-Route-Verbindung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>