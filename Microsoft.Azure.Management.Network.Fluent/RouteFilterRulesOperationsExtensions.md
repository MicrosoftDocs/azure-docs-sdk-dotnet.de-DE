<Type Name="RouteFilterRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFilterRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFilterRulesOperationsExtensions = class" />
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
            Erweiterungsmethoden für RouteFilterRulesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="ruleName">
            Der Name der Filterregel für Route.
            </param>
        <param name="routeFilterRuleParameters">
            Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Route im Routefilter angegebenen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="ruleName">
            Der Name der Regel.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Regel aus einem Routefilter an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="ruleName">
            Der Name der Filterregel für Route.
            </param>
        <param name="routeFilterRuleParameters">
            Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine Route im Routefilter angegebenen an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="ruleName">
            Der Name der Filterregel für Route.
            </param>
        <param name="routeFilterRuleParameters">
            Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Route im Routefilter angegebenen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="ruleName">
            Der Name der Regel.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Regel aus einem Routefilter an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="ruleName">
            Der Name der Regel.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Regel aus einem Routefilter ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle RouteFilterRules in einem Routefilter ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
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
            Ruft alle RouteFilterRules in einem Routefilter ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; UpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; UpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="routeFilterName">
            Der Name des Filters Route.
            </param>
        <param name="ruleName">
            Der Name der Filterregel für Route.
            </param>
        <param name="routeFilterRuleParameters">
            Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine Route im Routefilter angegebenen an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>