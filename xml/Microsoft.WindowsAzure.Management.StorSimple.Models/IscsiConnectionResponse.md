<Type Name="IscsiConnectionResponse" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse">
  <TypeSignature Language="C#" Value="public class IscsiConnectionResponse : Microsoft.Azure.AzureOperationResponse, System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IscsiConnectionResponse extends Microsoft.Azure.AzureOperationResponse implements class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class IscsiConnectionResponse&#xA;Inherits AzureOperationResponse&#xA;Implements IEnumerable(Of IscsiConnection)" />
  <TypeSignature Language="F#" Value="type IscsiConnectionResponse = class&#xA;    inherit AzureOperationResponse&#xA;    interface seq&lt;IscsiConnection&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="adae0-101">Die Liste der Verbindungsdetails iSCSI-Antwort-Modell.</span><span class="sxs-lookup"><span data-stu-id="adae0-101">The response model for the list of iscsi connection details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IscsiConnectionResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="adae0-102">Initialisiert eine neue Instanz der IscsiConnectionResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="adae0-102">Initializes a new instance of the IscsiConnectionResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of IscsiConnection)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt;" Usage="iscsiConnectionResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="adae0-103">Ruft die Sequenz von IscsiConnections ab.</span><span class="sxs-lookup"><span data-stu-id="adae0-103">Gets the sequence of IscsiConnections.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IscsiConnections">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt; IscsiConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt; IscsiConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse.IscsiConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property IscsiConnections As IList(Of IscsiConnection)" />
      <MemberSignature Language="F#" Value="member this.IscsiConnections : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse.IscsiConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnection&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="adae0-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="adae0-104">Optional.</span></span> <span data-ttu-id="adae0-105">Die Auflistung der iSCSI-Verbindungsdetails</span><span class="sxs-lookup"><span data-stu-id="adae0-105">The collection of iscsi connection details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="adae0-106">Ruft die Sequenz von IscsiConnections ab.</span><span class="sxs-lookup"><span data-stu-id="adae0-106">Gets the sequence of IscsiConnections.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>