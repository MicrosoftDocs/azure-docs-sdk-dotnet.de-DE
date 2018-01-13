<Type Name="PatchSchedulesOperationsExtensions" FullName="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PatchSchedulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PatchSchedulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für PatchSchedulesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt; scheduleEntriesProperty, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt; scheduleEntriesProperty, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, scheduleEntriesProperty, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="scheduleEntriesProperty" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="scheduleEntriesProperty">
            Liste der Patch-Zeitpläne für einen Redis Cache.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie oder Ersetzen Sie den Patchen Zeitplan für Redis-Cache (Premium SKU erfordert).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das Patchen Zeitplan für einen Redis Cache (Premium SKU erfordert).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; GetAsync (this Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; GetAsync(class Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft das Patchen Zeitplan für einen Redis Cache (Premium SKU erfordert).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>