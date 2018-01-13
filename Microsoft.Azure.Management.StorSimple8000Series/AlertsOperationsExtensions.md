<Type Name="AlertsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AlertsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AlertsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AlertsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AlertsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für AlertsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public static void Clear (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Clear(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.Clear(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Clear (operations As IAlertsOperations, parameters As ClearAlertRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Clear : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.Clear (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            Die Warnung löschen-Anforderung.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Deaktivieren Sie die Warnungen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ClearAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ClearAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ClearAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ClearAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ClearAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;ClearAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            Die Warnung löschen-Anforderung.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktivieren Sie die Warnungen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IAlertsOperations, resourceGroupName As String, managerName As String, Optional odataQuery As ODataQuery(Of AlertFilter) = null) As IPage(Of Alert)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManager (operations, resourceGroupName, managerName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <summary>
            Ruft alle Warnungen in einem Manager ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;ListByManagerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle Warnungen in einem Manager ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManagerNext (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManagerNext(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNext(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManagerNext (operations As IAlertsOperations, nextPageLink As String) As IPage(Of Alert)" />
      <MemberSignature Language="F#" Value="static member ListByManagerNext : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
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
            Ruft alle Warnungen in einem Manager ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerNextAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerNextAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNextAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerNextAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;ListByManagerNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
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
            Ruft alle Warnungen in einem Manager ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTestEmail">
      <MemberSignature Language="C#" Value="public static void SendTestEmail (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SendTestEmail(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmail(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SendTestEmail (operations As IAlertsOperations, deviceName As String, parameters As SendTestAlertEmailRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member SendTestEmail : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmail (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="parameters">
            Die warnungsbenachrichtigung per e-Mail-Anforderung senden Test.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Sendet eine Test-warnungsbenachrichtigung per e-Mail an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTestEmailAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SendTestEmailAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SendTestEmailAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmailAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SendTestEmailAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmailAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;SendTestEmailAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="parameters">
            Die warnungsbenachrichtigung per e-Mail-Anforderung senden Test.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Sendet eine Test-warnungsbenachrichtigung per e-Mail an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>