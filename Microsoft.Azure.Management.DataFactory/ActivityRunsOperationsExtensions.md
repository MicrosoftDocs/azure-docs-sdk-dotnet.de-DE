<Type Name="ActivityRunsOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityRunsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityRunsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityRunsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityRunsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ActivityRunsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByPipelineRun">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRun (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, DateTime startTime, DateTime endTime, string status = null, string activityName = null, string linkedServiceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRun(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, valuetype System.DateTime startTime, valuetype System.DateTime endTime, string status, string activityName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRun(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String,System.String,System.String,System.DateTime,System.DateTime,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineRun (operations As IActivityRunsOperations, resourceGroupName As String, factoryName As String, runId As String, startTime As DateTime, endTime As DateTime, Optional status As String = null, Optional activityName As String = null, Optional linkedServiceName As String = null) As IPage(Of ActivityRun)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRun : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string * string * string * DateTime * DateTime * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRun (operations, resourceGroupName, factoryName, runId, startTime, endTime, status, activityName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="factoryName">
            Die Factory-Namen.
            </param>
        <param name="runId">
            Die Pipeline Bezeichner ausführen.
            </param>
        <param name="startTime">
            Die Startzeit der Aktivität wird im ISO8601-Format ausgeführt.
            </param>
        <param name="endTime">
            Die Endzeit der Aktivität wird im ISO8601-Format ausgeführt.
            </param>
        <param name="status">
            Führen Sie der Status der Pipeline.
            </param>
        <param name="activityName">
            Der Name der Aktivität.
            </param>
        <param name="linkedServiceName">
            Der Name des verknüpften Diensts.
            </param>
        <summary>
            Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineRunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunAsync (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, DateTime startTime, DateTime endTime, string status = null, string activityName = null, string linkedServiceName = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunAsync(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, valuetype System.DateTime startTime, valuetype System.DateTime endTime, string status, string activityName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunAsync(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String,System.String,System.String,System.DateTime,System.DateTime,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRunAsync : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string * string * string * DateTime * DateTime * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunAsync (operations, resourceGroupName, factoryName, runId, startTime, endTime, status, activityName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions/&lt;ListByPipelineRunAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="factoryName">
            Die Factory-Namen.
            </param>
        <param name="runId">
            Die Pipeline Bezeichner ausführen.
            </param>
        <param name="startTime">
            Die Startzeit der Aktivität wird im ISO8601-Format ausgeführt.
            </param>
        <param name="endTime">
            Die Endzeit der Aktivität wird im ISO8601-Format ausgeführt.
            </param>
        <param name="status">
            Führen Sie der Status der Pipeline.
            </param>
        <param name="activityName">
            Der Name der Aktivität.
            </param>
        <param name="linkedServiceName">
            Der Name des verknüpften Diensts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineRunNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRunNext (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRunNext(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNext(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineRunNext (operations As IActivityRunsOperations, nextPageLink As String) As IPage(Of ActivityRun)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRunNext : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
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
            Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineRunNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunNextAsync (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunNextAsync(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNextAsync(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRunNextAsync : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions/&lt;ListByPipelineRunNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
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
            Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>