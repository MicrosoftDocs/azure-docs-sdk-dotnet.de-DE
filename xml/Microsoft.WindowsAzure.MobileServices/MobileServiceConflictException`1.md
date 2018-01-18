<Type Name="MobileServiceConflictException&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class MobileServiceConflictException&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceConflictException`1&lt;T&gt; extends Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException`1" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceConflictException(Of T)&#xA;Inherits MobileServiceConflictException" />
  <TypeSignature Language="F#" Value="type MobileServiceConflictException&lt;'T&gt; = class&#xA;    inherit MobileServiceConflictException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="d4e90-101">Enthält Details zur HTTP-Antwort mit dem Statuscode "Konflikts"</span><span class="sxs-lookup"><span data-stu-id="d4e90-101">Provides details of http response with status code of 'Conflict'</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceConflictException (Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, !T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException`1.#ctor(Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As MobileServiceInvalidOperationException, item As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException&lt;'T&gt; : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException * 'T -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException&lt;'T&gt; (source, item)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="source">
            <span data-ttu-id="d4e90-102">Die innere Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="d4e90-102">The inner exception.</span></span>
            </param>
        <param name="item">
            <span data-ttu-id="d4e90-103">Die aktuelle Instanz vom Server, dem für der Konflikt aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="d4e90-103">The current instance from the server that the conflict occurred for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d4e90-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d4e90-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public T Item { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Item" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException`1.Item" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Item As T" />
      <MemberSignature Language="F#" Value="member this.Item : 'T" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException&lt;'T&gt;.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4e90-105">Die aktuelle Instanz vom Server, dem für die Vorbedingung nicht erfüllt.</span><span class="sxs-lookup"><span data-stu-id="d4e90-105">The current instance from the server that the precondition failed for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>