<Type Name="CheckGroupMembershipParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner">
  <TypeSignature Language="C#" Value="public class CheckGroupMembershipParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckGroupMembershipParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckGroupMembershipParametersInner" />
  <TypeSignature Language="F#" Value="type CheckGroupMembershipParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2304f-101">Anforderungsparameter für IsMemberOf API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="2304f-101">Request parameters for IsMemberOf API call.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckGroupMembershipParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2304f-102">Initialisiert eine neue Instanz der CheckGroupMembershipParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2304f-102">Initializes a new instance of the CheckGroupMembershipParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckGroupMembershipParametersInner (string groupId, string memberId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string groupId, string memberId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (groupId As String, memberId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner : string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner (groupId, memberId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="memberId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupId"><span data-ttu-id="2304f-103">Die Objekt-ID des zu überprüfenden Gruppe.</span><span class="sxs-lookup"><span data-stu-id="2304f-103">The object ID of the group to check.</span></span></param>
        <param name="memberId"><span data-ttu-id="2304f-104">Die Objekt-ID des Kontakts, Gruppen, Benutzer oder Dienstprinzipal für die Mitgliedschaft in der angegebenen Gruppe überprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="2304f-104">The object ID of the contact, group, user, or service principal to check for membership in the specified group.</span></span></param>
        <summary>
            <span data-ttu-id="2304f-105">Initialisiert eine neue Instanz der CheckGroupMembershipParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2304f-105">Initializes a new instance of the CheckGroupMembershipParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupId">
      <MemberSignature Language="C#" Value="public string GroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner.GroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupId As String" />
      <MemberSignature Language="F#" Value="member this.GroupId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner.GroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="groupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2304f-106">Ruft ab oder legt die Objekt-ID des zu überprüfenden Gruppe.</span><span class="sxs-lookup"><span data-stu-id="2304f-106">Gets or sets the object ID of the group to check.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemberId">
      <MemberSignature Language="C#" Value="public string MemberId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MemberId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner.MemberId" />
      <MemberSignature Language="VB.NET" Value="Public Property MemberId As String" />
      <MemberSignature Language="F#" Value="member this.MemberId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner.MemberId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="memberId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2304f-107">Abrufen oder Festlegen der Objekt-ID des Kontakts, Gruppe, Benutzer oder Dienst Prinzipal für die Mitgliedschaft in der angegebenen Gruppe überprüft.</span><span class="sxs-lookup"><span data-stu-id="2304f-107">Gets or sets the object ID of the contact, group, user, or service principal to check for membership in the specified group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="checkGroupMembershipParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2304f-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2304f-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2304f-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2304f-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>