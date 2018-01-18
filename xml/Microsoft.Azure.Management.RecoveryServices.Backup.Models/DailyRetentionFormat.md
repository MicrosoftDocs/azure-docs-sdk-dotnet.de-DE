<Type Name="DailyRetentionFormat" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat">
  <TypeSignature Language="C#" Value="public class DailyRetentionFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DailyRetentionFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class DailyRetentionFormat" />
  <TypeSignature Language="F#" Value="type DailyRetentionFormat = class" />
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
            <span data-ttu-id="c6efb-101">Tägliche Beibehaltung-Format.</span><span class="sxs-lookup"><span data-stu-id="c6efb-101">Daily retention format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DailyRetentionFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6efb-102">Initialisiert eine neue Instanz der DailyRetentionFormat-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6efb-102">Initializes a new instance of the DailyRetentionFormat class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DailyRetentionFormat (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt; daysOfTheMonth = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt; daysOfTheMonth) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional daysOfTheMonth As IList(Of Day) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat daysOfTheMonth" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="daysOfTheMonth" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt;" />
      </Parameters>
      <Docs>
        <param name="daysOfTheMonth"><span data-ttu-id="c6efb-103">Liste der Tage des Monats.</span><span class="sxs-lookup"><span data-stu-id="c6efb-103">List of days of the month.</span></span></param>
        <summary>
            <span data-ttu-id="c6efb-104">Initialisiert eine neue Instanz der DailyRetentionFormat-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6efb-104">Initializes a new instance of the DailyRetentionFormat class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DaysOfTheMonth">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt; DaysOfTheMonth { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt; DaysOfTheMonth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat.DaysOfTheMonth" />
      <MemberSignature Language="VB.NET" Value="Public Property DaysOfTheMonth As IList(Of Day)" />
      <MemberSignature Language="F#" Value="member this.DaysOfTheMonth : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat.DaysOfTheMonth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="daysOfTheMonth")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.Day&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6efb-105">Ruft ab oder legt die Liste der Tage des Monats.</span><span class="sxs-lookup"><span data-stu-id="c6efb-105">Gets or sets list of days of the month.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>