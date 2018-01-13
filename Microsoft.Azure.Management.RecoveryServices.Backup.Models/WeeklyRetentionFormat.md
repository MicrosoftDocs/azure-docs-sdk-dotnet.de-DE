<Type Name="WeeklyRetentionFormat" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat">
  <TypeSignature Language="C#" Value="public class WeeklyRetentionFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WeeklyRetentionFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class WeeklyRetentionFormat" />
  <TypeSignature Language="F#" Value="type WeeklyRetentionFormat = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="69c85-101">Wöchentliche Beibehaltung-Format.</span><span class="sxs-lookup"><span data-stu-id="69c85-101">Weekly retention format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WeeklyRetentionFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="69c85-102">Initialisiert eine neue Instanz der WeeklyRetentionFormat-Klasse.</span><span class="sxs-lookup"><span data-stu-id="69c85-102">Initializes a new instance of the WeeklyRetentionFormat class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WeeklyRetentionFormat (System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; daysOfTheWeek = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt; weeksOfTheMonth = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; daysOfTheWeek, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt; weeksOfTheMonth) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat.#ctor(System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek}},System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional daysOfTheWeek As IList(Of Nullable(Of DayOfWeek)) = null, Optional weeksOfTheMonth As IList(Of Nullable(Of WeekOfMonth)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat (daysOfTheWeek, weeksOfTheMonth)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="daysOfTheWeek" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt;" />
        <Parameter Name="weeksOfTheMonth" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="daysOfTheWeek"><span data-ttu-id="69c85-103">Liste der Tage der Woche.</span><span class="sxs-lookup"><span data-stu-id="69c85-103">List of days of the week.</span></span></param>
        <param name="weeksOfTheMonth"><span data-ttu-id="69c85-104">Liste der Wochen des Monats.</span><span class="sxs-lookup"><span data-stu-id="69c85-104">List of weeks of month.</span></span></param>
        <summary>
            <span data-ttu-id="69c85-105">Initialisiert eine neue Instanz der WeeklyRetentionFormat-Klasse.</span><span class="sxs-lookup"><span data-stu-id="69c85-105">Initializes a new instance of the WeeklyRetentionFormat class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DaysOfTheWeek">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; DaysOfTheWeek { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; DaysOfTheWeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat.DaysOfTheWeek" />
      <MemberSignature Language="VB.NET" Value="Public Property DaysOfTheWeek As IList(Of Nullable(Of DayOfWeek))" />
      <MemberSignature Language="F#" Value="member this.DaysOfTheWeek : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat.DaysOfTheWeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="daysOfTheWeek")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69c85-106">Ruft ab oder legt die Liste der Tage der Woche.</span><span class="sxs-lookup"><span data-stu-id="69c85-106">Gets or sets list of days of the week.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WeeksOfTheMonth">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt; WeeksOfTheMonth { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt; WeeksOfTheMonth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat.WeeksOfTheMonth" />
      <MemberSignature Language="VB.NET" Value="Public Property WeeksOfTheMonth As IList(Of Nullable(Of WeekOfMonth))" />
      <MemberSignature Language="F#" Value="member this.WeeksOfTheMonth : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat.WeeksOfTheMonth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weeksOfTheMonth")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeekOfMonth&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69c85-107">Ruft ab, oder legt ihn fest Liste der Wochen des Monats.</span><span class="sxs-lookup"><span data-stu-id="69c85-107">Gets or sets list of weeks of month.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>