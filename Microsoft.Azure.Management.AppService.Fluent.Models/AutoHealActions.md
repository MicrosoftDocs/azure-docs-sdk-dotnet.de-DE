<Type Name="AutoHealActions" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions">
  <TypeSignature Language="C#" Value="public class AutoHealActions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoHealActions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoHealActions" />
  <TypeSignature Language="F#" Value="type AutoHealActions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Aktionen, übernehmen die-Autom Modul, wenn eine Regel ausgelöst wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealActions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AutoHealActions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealActions (Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt; actionType = null, Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction customAction = null, string minProcessExecutionTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt; actionType, class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction customAction, string minProcessExecutionTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.#ctor(System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType},Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionType As Nullable(Of AutoHealActionType) = null, Optional customAction As AutoHealCustomAction = null, Optional minProcessExecutionTime As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions (actionType, customAction, minProcessExecutionTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt;" />
        <Parameter Name="customAction" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction" />
        <Parameter Name="minProcessExecutionTime" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actionType">Vordefinierte auszuführende Aktion. Folgende Werte sind möglich: "Wiederverwenden', 'LogEvent',"CustomAction"</param>
        <param name="customAction">Die benutzerdefinierte Aktion, die ausgeführt werden.</param>
        <param name="minProcessExecutionTime">Minimale Zeit, die der Prozess ausgeführt werden muss, bevor Sie die Aktion</param>
        <summary>
            Initialisiert eine neue Instanz der AutoHealActions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt; ActionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt; ActionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.ActionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionType As Nullable(Of AutoHealActionType)" />
      <MemberSignature Language="F#" Value="member this.ActionType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.ActionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActionType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest vordefinierten auszuführende Aktion. Folgende Werte sind möglich: "Wiederverwenden', 'LogEvent',"CustomAction"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomAction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction CustomAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction CustomAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.CustomAction" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomAction As AutoHealCustomAction" />
      <MemberSignature Language="F#" Value="member this.CustomAction : Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.CustomAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealCustomAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest benutzerdefinierten Aktion, die ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinProcessExecutionTime">
      <MemberSignature Language="C#" Value="public string MinProcessExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinProcessExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.MinProcessExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MinProcessExecutionTime As String" />
      <MemberSignature Language="F#" Value="member this.MinProcessExecutionTime : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions.MinProcessExecutionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minProcessExecutionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die minimale Zeit, die der Prozess ausgeführt werden muss, bevor Sie die Aktion
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>