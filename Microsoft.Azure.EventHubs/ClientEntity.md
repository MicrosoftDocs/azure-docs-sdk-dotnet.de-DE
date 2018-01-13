<Type Name="ClientEntity" FullName="Microsoft.Azure.EventHubs.ClientEntity">
  <TypeSignature Language="C#" Value="public abstract class ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ClientEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ClientEntity" />
  <TypeSignature Language="F#" Value="type ClientEntity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0582b-101">Vertrag für alle Client-Entitäten mit Open-schließen/Abort Zustand m/c Main Zwecke: CloseAll verknüpften Entitäten</span><span class="sxs-lookup"><span data-stu-id="0582b-101">Contract for all client entities with Open-Close/Abort state m/c main-purpose: closeAll related entities</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ClientEntity (string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.ClientEntity.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (clientId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.ClientEntity : string -&gt; Microsoft.Azure.EventHubs.ClientEntity" Usage="new Microsoft.Azure.EventHubs.ClientEntity clientId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ClientEntity.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Azure.EventHubs.ClientEntity.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0582b-102">Ruft die Client-ID.</span><span class="sxs-lookup"><span data-stu-id="0582b-102">Gets the client ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="public void Close ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Close() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.ClientEntity.Close" />
      <MemberSignature Language="VB.NET" Value="Public Sub Close ()" />
      <MemberSignature Language="F#" Value="member this.Close : unit -&gt; unit" Usage="clientEntity.Close " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0582b-103">Schließt die ClientEntity an.</span><span class="sxs-lookup"><span data-stu-id="0582b-103">Closes the ClientEntity.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.ClientEntity.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clientEntity.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0582b-104">Schließt die ClientEntity an.</span><span class="sxs-lookup"><span data-stu-id="0582b-104">Closes the ClientEntity.</span></span>
            </summary>
        <returns><span data-ttu-id="0582b-105">Der asynchrone Vorgang</span><span class="sxs-lookup"><span data-stu-id="0582b-105">The asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextId">
      <MemberSignature Language="C#" Value="protected static long GetNextId ();" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig int64 GetNextId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.ClientEntity.GetNextId" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GetNextId () As Long" />
      <MemberSignature Language="F#" Value="static member GetNextId : unit -&gt; int64" Usage="Microsoft.Azure.EventHubs.ClientEntity.GetNextId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRetryPolicyUpdate">
      <MemberSignature Language="C#" Value="protected virtual void OnRetryPolicyUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnRetryPolicyUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.ClientEntity.OnRetryPolicyUpdate" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnRetryPolicyUpdate ()" />
      <MemberSignature Language="F#" Value="abstract member OnRetryPolicyUpdate : unit -&gt; unit&#xA;override this.OnRetryPolicyUpdate : unit -&gt; unit" Usage="clientEntity.OnRetryPolicyUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0582b-106">Abgeleitete Entität zur Überschreibung für richtlinienaktualisierungen versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="0582b-106">Derived entity to override for retry policy updates.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ClientEntity.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.EventHubs.RetryPolicy with get, set" Usage="Microsoft.Azure.EventHubs.ClientEntity.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0582b-107">Ruft die <see cref="M:Microsoft.Azure.EventHubs.RetryPolicy.#ctor" /> für die ClientEntity.</span><span class="sxs-lookup"><span data-stu-id="0582b-107">Gets the <see cref="M:Microsoft.Azure.EventHubs.RetryPolicy.#ctor" /> for the ClientEntity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>